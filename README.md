# Versionamento Semântico

O **autoupdater** utiliza o versionamento semântico para identificar e organizar suas versões, se atente as definições antes de publicar qualquer release:

## Alpha (1.0.0-alpha.x)
Versão de pré-lançamento inicial para desenvolvedores ou testes internos, geralmente com funcionalidades incompletas e muitos bugs.  
**Quando usar**: Quando o desenvolvimento de uma nova versão está começando e você quer compartilhar com outros desenvolvedores ou testar funcionalidades básicas.  
**Exemplo**: `1.0.0-alpha.1`, `1.0.0-alpha.2`.

## Beta (1.0.0-beta.x)
Versão de pré-lançamento mais avançada que o _alpha_, com funcionalidades mais completas, mas ainda podendo conter bugs.  
**Quando usar**: Quando você deseja que usuários ou testers externos usem a versão para detectar problemas antes do lançamento oficial.  
**Exemplo**: `1.0.0-beta.1`, `1.0.0-beta.2`.

## RC (Release Candidate)
Versão quase final, muito próxima do lançamento. Apenas pequenas correções ou ajustes são feitos a partir deste ponto.  
**Quando usar**: Quando você acredita que a versão está praticamente pronta para ser lançada, mas deseja uma última rodada de testes para confirmar.  
**Exemplo**: `1.0.0-rc.1`, `1.0.0-rc.2`.

## Final Release (1.0.0)
Versão final e estável disponibilizada ao público.  
**Quando usar**: Após todas as fases de testes, ajustes e correções (alpha, beta, e RC).  
**Exemplo de versão**: `1.0.0`.

## Major (x.0.0)
Esta é a versão que representa grandes mudanças no software.  
**Quando usar**: Quando há modificações que podem quebrar a compatibilidade com versões anteriores (breaking changes).  
**Exemplo**: Migrar para uma nova API, refatorar completamente o código, ou alterar comportamentos centrais do sistema.  
**Exemplo de versão**: `2.0.0`, `3.0.0`.

## Minor (1.x.0)
Incrementa-se o número _minor_ quando há adição de funcionalidades novas que não quebram a compatibilidade com versões anteriores.  
**Quando usar**: Quando você adiciona novas funcionalidades ou melhora as existentes, mantendo a compatibilidade com versões anteriores.  
**Exemplo**: Adicionar um novo recurso ou melhorar o desempenho de uma função sem modificar sua interface.  
**Exemplo de versão**: `1.1.0`, `1.2.0`.

## Patch (1.0.x)
Incrementa-se o número _patch_ quando são feitas pequenas correções de bugs ou ajustes no software que não afetam a API ou as funcionalidades existentes.  
**Quando usar**: Correções de bugs e pequenas melhorias que não alteram a interface pública do código.  
**Exemplo**: Corrigir um bug em uma funcionalidade existente ou otimizar o desempenho sem alterar a lógica.  
**Exemplo de versão**: `1.0.1`, `1.0.2`.
