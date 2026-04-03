# Auditoria de Segurança – Botium Toys

Este projeto faz parte do meu curso de Cibersegurança e consiste em uma atividade prática de auditoria de segurança. O objetivo foi identificar riscos, avaliar controles e propor melhorias para garantir conformidade com padrões como PCI DSS, RGPD e SOC.

## Escopo da Auditoria
- Avaliação do programa de segurança completo da Botium Toys.
- Revisão dos ativos gerenciados pelo departamento de TI.
- Análise de controles administrativos, técnicos e físicos.
- Verificação de conformidade com normas internacionais.

## Principais Riscos Identificados
- Falta de criptografia para dados sensíveis.
- Ausência de plano de recuperação de desastres e backups.
- Política de senhas fraca e sem gerenciamento centralizado.
- Acesso excessivo aos dados por todos os funcionários.
- Sistemas legados sem cronograma de manutenção.

## Controles Existentes
- Firewall e antivírus instalados.
- CCTV, fechaduras e sistema de prevenção de incêndios.
- Políticas de senha básicas (necessitam reforço).

## Controles Ausentes
- IDS/IPS.
- Criptografia.
- Backups regulares.
- Privilégio mínimo e separação de funções.
- Sistema de gerenciamento de senhas.

## Conformidade
- **PCI DSS:** Não, Não, Não, Não  
- **RGPD:** Não, Sim, Não, Sim  
- **SOC:** Sim, Não, Sim, Não  

## Recomendações
1. Implementar criptografia para dados de cartão e PII/SPII.  
2. Criar plano de recuperação de desastres e rotina de backups.  
3. Reforçar política de senhas com sistema de gerenciamento.  
4. Aplicar controles de acesso com base no princípio do menor privilégio.  
5. Estabelecer cronograma de manutenção para sistemas legados.  
6. Classificação e inventário de dados para atender ao RGPD.  

## Documentos da Auditoria

- [Escopo, objetivos e relatório de avaliação de riscos](Botium%20Toys_%20Escopo%2C%20objetivos%20e%20relatório%20de%20avaliação%20de%20riscos.pdf)
- [Categorias de controle](Categorias%20de%20controle.pdf)
- [Lista de verificação de controles e conformidade](Lista%20de%20verificação%20de%20controles%20e%20conformidade.pdf)


