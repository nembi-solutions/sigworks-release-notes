# Manual de Uso – Importação de Desembolso

Permite definir a distribuição de unidades ao longo dos meses diretamente no upload da Linha de Base, utilizando um template com cabeçalho dinâmico.

> Introduzido na **v1.58**

---

## Quando utilizar

A importação de desembolso deve ser utilizada quando for necessário:

- Controlar a distribuição mensal de unidades;
- Garantir que o planejamento reflita corretamente o período da Linha de Base;
- Evitar ajustes manuais posteriores no sistema.

---

## Como utilizar

### 1. Cadastro da Linha de Base

Ao cadastrar uma nova Linha de Base, localize a opção:

- **Importar Desembolso?**

Essa opção deve ser **marcada** para habilitar a funcionalidade de importação de desembolso.

> Caso a opção não seja marcada, o sistema seguirá o fluxo padrão, sem considerar distribuição mensal via upload.

---

### 2. Geração do Template

Após marcar a opção **"Importar Desembolso?"**, o botão **Template** ficará disponível.

Ao clicar em **Template**:

- O sistema gera automaticamente um arquivo de template;
- O cabeçalho do template é criado de forma **dinâmica**;
- Os meses exibidos correspondem exatamente ao período definido na Linha de Base.

Exemplo de cabeçalho gerado:
- Jan/2025
- Fev/2025
- Mar/2025
- Abr/2025

---

### 3. Preenchimento do Template

No template gerado:

- Cada coluna de mês representa a quantidade de unidades a serem desembolsadas naquele período;
- O usuário deve preencher os valores conforme o planejamento mensal;
- Os valores informados serão utilizados diretamente no cálculo e distribuição do desembolso no sistema.

⚠️ **Atenção**  
- Todos os meses do período devem ser considerados;
- O preenchimento deve respeitar o formato do template gerado, sem alterar cabeçalhos ou estrutura.

---

### 4. Upload do Arquivo

Após o preenchimento:

1. Salve o arquivo;
2. Realize o upload normalmente pelo sistema;
3. O sistema irá validar:
   - Coerência dos meses informados;
   - Compatibilidade com o período da Linha de Base;
   - Consistência dos valores de desembolso.

Se todas as validações forem atendidas, o desembolso será importado e aplicado automaticamente.

---

## Resultado

Após a importação bem-sucedida:

- A distribuição mensal passa a fazer parte da Linha de Base;
- Os dados ficam disponíveis para visualização e acompanhamento;
- O planejamento reflete fielmente os valores informados no upload.
