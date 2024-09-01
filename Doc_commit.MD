# Padronização de Commits e Changelog

## 1. Commits

### 1.1 Objetivo
- Manter histórico de alterações
- Centralizar a distribuição de código

### 1.2 Commits Semânticos

#### Formato
```
tipo: descrição
```

#### Tipos
- `feat`: nova feature
- `fix`: correção
- `docs`: mudança em documentação
- `style`: mudança de estilo sem alterar funções
- `refactor`: refatoração de código

#### Exemplos
- `feat: adicionar sistema de autenticação`
- `fix: corrigir bug na validação de formulário`
- `docs: atualizar README com novas instruções de instalação`
- `style: ajustar espaçamento no cabeçalho`
- `refactor: otimizar função de busca`

**Nota**: Commits devem sempre começar com verbos no infinitivo, indicando ações.

## 2. Versionamento

### Formato
```
x.y.z
```

- `z`: correções pequenas
- `y`: alterações pequenas
- `x`: alterações grandes com potencial de quebra

## 3. Changelog

### Formato
```
[versão] - data (yyyy-mm-dd)
+ tipo:
    - lista de alterações
```

### Exemplo

```markdown
# Changelog

## [0.2.3] - 2024-01-01
### Melhorias
- Exemplo de melhoria

## [0.2.2] - 2023-12-15
### Correções
- Correção de bug na interface do usuário

## [0.2.1] - 2023-12-01
### Adições
- Nova funcionalidade de exportação de relatórios

## [0.2.0] - 2023-11-15
### Mudanças
- Refatoração completa do módulo de autenticação

## [0.1.0] - 2023-11-01
### Adições
- Lançamento inicial da aplicação
```

## 4. Relação entre Commits e Changelog

Os commits devem refletir as mudanças listadas no changelog. Por exemplo:

```
0.2.3 - fix: corrigir renderização de gráficos na dashboard
0.2.2 - style: ajustar espaçamento nos botões da navbar
0.2.1 - feat: implementar exportação de relatórios em PDF
0.2.0 - refactor: reestruturar módulo de autenticação
0.1.0 - feat: versão inicial da aplicação
```

Seguindo essas diretrizes, você manterá um histórico claro e organizado das alterações em seu projeto, facilitando a colaboração e o acompanhamento do desenvolvimento.
