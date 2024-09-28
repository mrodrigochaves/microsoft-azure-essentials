# Principais Ferramentas e Mecanismos

## Portal do Azure:
- **Interface gráfica**: Ideal para usuários iniciantes e tarefas simples.
- Permite criar e gerenciar recursos de forma visual.
- Limitado para grandes implantações ou automação complexa.

## Azure PowerShell:
- **Linguagem de script**: Permite automatizar tarefas complexas e criar scripts personalizados.
- Grande flexibilidade e controle sobre os recursos do Azure.
- Ideal para tarefas repetitivas ou integração com outros sistemas.

## Azure CLI:
- **Interface de linha de comando**: Similar ao PowerShell, mas com sintaxe diferente.
- Automatização em scripts e integração com ferramentas de linha de comando.

## Azure Resource Manager:
- **Modelo de gerenciamento**: Permite definir e gerenciar grupos de recursos e suas dependências.
- Utiliza templates (JSON ou Bicep) para definir a infraestrutura.
- Base para outras ferramentas de automação.

## Azure Bicep:
- **Linguagem DSL**: Mais concisa e legível que JSON para definir templates do Azure Resource Manager.
- Integração com o Azure Resource Manager.

## Azure Arc:
- **Extensão do Azure**: Permite gerenciar recursos híbridos e multi-cloud.
- Utiliza o Azure Resource Manager para gerenciar recursos fora do Azure.

## Quando usar cada ferramenta:
- **Portal do Azure**: Tarefas simples, usuários iniciantes.
- **Azure PowerShell e Azure CLI**: Automação, scripts personalizados, integração com outros sistemas.
- **Azure Resource Manager e Bicep**: Definição e gerenciamento de infraestrutura complexa, templates reutilizáveis.
- **Azure Arc**: Gerenciamento de recursos híbridos e multi-cloud.
