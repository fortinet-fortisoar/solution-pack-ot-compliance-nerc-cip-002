| [Home](../README.md) |
| -------------------- |

  # Contents

The **OT - Compliance - NERC CIP-002** solution pack contains the following resources.

## Dashboards

| Name                                                | Description                                                                                                                                                                                                                                                                                                          |
| :-------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| NERC CIP 002-5.1a - BES Cyber System Categorization | Display Cyber Systems by Impact, by Entity Type, by Digital Control System, Cyber Asset by Category, Violations Impact Evaluation, Overdue Impact Evaluation, Cyber Systems - Entity Type vs Digital Control System, Cyber Systems - BES Impact vs Entity Type, Cyber Systems - BES Impact vs Digital Control System |

## Picklist

| Name                |
| :------------------ |
| BES Control Systems |
| BES Entity Type     |
| BES Impact          |

## Module Schema

| Name              | Description                                                                      |
| :---------------- | :------------------------------------------------------------------------------- |
| BES Cyber Systems | Contains the record for BES Cyber System over which BES Impact can be evaluated. |


## Widgets

| Name                  | Description                                                                                                                                                    |
| :-------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BES Impact Evaluation | The widget serves to compute the impact on Cyber Systems within the Bulk Electric System (BES) in accordance with the specifications outlined in NERC CIP 002. |


## Roles

| Name                 | Description                                                                |
| :------------------- | :------------------------------------------------------------------------- |
| Full App Permissions | Create, Read, Update, and Delete permission for module *BES Cyber Systems* |
| SOC Manager          | Create, Read, Update, and Delete permission for module *BES Cyber Systems* |
| SOC Analyst          | Create, Read, and Update permission for module *BES Cyber Systems*         |

## Report

| Name                                               | Description                                                                                           |
| :------------------------------------------------- | :---------------------------------------------------------------------------------------------------- |
| NERC CIP 002-5.1a: BES Impact Evaluation Reminder  | Generate a report for BES Cyber systems that have undergone assessment of BES Impact for over a year. |
| NERC CIP 002-5.1a: BES Impact Non-Evaluated System | Generate a report for BES Cyber systems that haven't undergone assessment of BES Impact.              |



## Playbook Collection

| 02 - Use Case - NERC CIP-002 |
| :--------------------------: |

| Playbook Name                             | Description                                                                                                                             |
| :---------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| Scenario - Create BES Cyber System Record | Creates samples record of BES Cyber Systems to evaluate Impact.                                                                         |
| BES Cyber System Impact Report Generation | Generate report of BES Cyber System Impact last assessment.                                                                             |
| BES Impact Evaluation - Reminder          | Sends reminder to re-evaluate the impact of the Bulk Electric System (BES) Cyber System, which was last evaluated more than a year ago. |
| BES Impact Evaluation - Violations        | Generates Non-Evaluated BES Cyber System Report and report its to delegate.                                                             |
| Assign BES Cyber System Category          | Tags assets with BES Cyber System Categories.                                                                                           |



## System View

| Name          |
| :------------ |
| OT Compliance |


>**Warning:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| --------------------------------------- | ----------------------------------------- | ------------------- |