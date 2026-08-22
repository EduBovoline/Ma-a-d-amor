# Política de Segurança — Maçã d'Amor

A segurança da informação e a proteção dos dados dos clientes são prioridades no desenvolvimento e na manutenção deste site institucional.

---

## 1. Diretrizes de Segurança Implementadas

- **Nenhum Dado Sensível no Código**: O código-fonte deste projeto não contém credenciais de banco de dados, chaves de API secretas, senhas ou dados pessoais restritos.
- **Sanitização de Formulários e Links**:
  - Todas as integrações com o WhatsApp utilizam codificação segura via `encodeURIComponent` para mitigar injeções e quebras de parâmetros na URL.
  - Links externos abertos em nova aba utilizam obrigatoriamente `rel="noopener noreferrer"` para mitigar riscos de *tabnabbing* reverso.
- **Cabeçalhos e Metas de Proteção HTTP**:
  - `X-Content-Type-Options: nosniff`: Previne que o navegador tente inferir tipos MIME diferentes dos declarados.
  - `Referrer-Policy: strict-origin-when-cross-origin`: Protege o envio de dados do referenciador em requisições de origens cruzadas.
  - Carregamento de scripts e fontes locais hospedados na própria infraestrutura ou origens confiáveis e seguras com HTTPS.

---

## 2. Reporte de Vulnerabilidades

Caso identifique qualquer inconsistência ou possível vulnerabilidade de segurança:

1. **Não divulgue publicamente**: Por favor, não crie *Issues* públicas no GitHub descrevendo falhas de segurança.
2. **Entre em contato**: Envie um e-mail com os detalhes técnicos para a equipe responsável pela administração do projeto ou contate a **Vocação Comunicação & Marketing**.
3. **Prazo de Resposta**: Comprometemo-nos a avaliar e aplicar correções em tempo hábil.
