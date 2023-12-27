| [Home](../README.md) |
| -------------------- |

  # Contents

The **OT - Compliance - NERC CIP-002** solution pack contains the following resources.

## Dashboards

<table>
        <tr>
            <th>Name</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>NERC CIP 002 - 5.1a - BES Cyber System Categorization</td>
            <td>Displays following visualizations:
                <ul>
                    <li>Cyber Systems by Impact</li>
                    <li>Cyber Systems by Entity Type</li>
                    <li>Cyber Systems Digital Control System</li>
                    <li>Cyber Asset Category</li>
                    <li>Impact Evaluation - Violations</li>
                    <li>Impact Evaluation - Overdue</li>
                    <li>Cyber Systems - Entity Type vs Digital Control System</li>
                    <li>Cyber Systems - BES Impact vs Entity Type</li>
                    <li>Cyber Systems - BES Impact vs Digital Control System</li>
                </ul>        
            </td>
        </tr>
    </tbody>
</table>


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

| Name                  | Description                                                                                                                                            |
|:----------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------|
| BES Impact Evaluation | This widget computes the impact on Cyber Systems within the Bulk Electric System (BES) in accordance with the specifications outlined in NERC CIP 002. |
| Record Distribution   | This widget helps visualize items/records and their correlations in different levels based on a specified grouping criteria.                           |


## Roles

| Name                 | Description                                                                |
| :------------------- | :------------------------------------------------------------------------- |
| Full App Permissions | Create, Read, Update, and Delete permission for module *BES Cyber Systems* |
| SOC Manager          | Create, Read, Update, and Delete permission for module *BES Cyber Systems* |
| SOC Analyst          | Create, Read, and Update permission for module *BES Cyber Systems*         |

## Report

| Name                                                 | Description                                                                                            |
|:-----------------------------------------------------|:-------------------------------------------------------------------------------------------------------|
| NERC CIP 002 - 5.1a: BES Impact Evaluation Reminder  | Generates a report for BES Cyber systems that have undergone assessment of BES Impact for over a year. |
| NERC CIP 002 - 5.1a: BES Impact Non-Evaluated System | Generates a report for BES Cyber systems that haven't undergone assessment of BES Impact.              |

## Scenario Record set 

<table>
    <tr>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>NERC CIP - 002 BES Cyber Systems Sample Record</td>
        <td>This scenario creates three Bulk Electric System (BES) Cyber System records:
            <ul>
                <li>Great Wind Energy - Plant GWE41</li>
                <li>Northeast Power Management Company - Plant NPMC61</li>
                <li>Northern Energy - Plant NE981</li>
            </ul>
            These records capture essential information such as the <strong><em>Entity type</em></strong> and the associated <strong><em>Digital Control System</em></strong>.
            <p>These records help users correlate assets within the electric grid infrastructure. Additionally, a user-friendly interface includes an <strong>Evaluate Impact</strong> button that triggers the calculation of BES Impact.</p></td>
    </tr>
</table>

## Playbook Collection

| 02 - Use Case - NERC CIP-002 |
| :--------------------------: |


| Playbook Name                             | Description                                                                                                                             |
|:------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|
| Scenario - Create BES Cyber System Record | Creates samples record of BES Cyber Systems to evaluate Impact.                                                                         |
| BES Cyber System Impact Report Generation | Generates report of BES Cyber System Impact last assessment.                                                                            |
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