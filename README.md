# Manage Datasets

Creates and lists datasets allowing you to save, list, and preview datasets. Datasets enable you to filter module data based on the defined filtration criteria. 

An example of using the manage datasets widget would be adding this widget to the **Threat Feeds** tab of the `Threat Intel Management` page and then creating a dataset based on the defined filtration criteria.  

## Version Information

**Version**: 1.0.0  

**Certified**: Yes

**Publisher**: Fortinet  

**Compatibility**: 7.2.0 and later

**Applicable**: View Panel

## Manage Datasets Views

**Manage Datasets Edit View**:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-manage-datasets/release/1.0.0/docs/media/manage-datasets-edit-view.png" alt="Editing the Manage Datasets Widget" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

**Manage Datasets - Threat Intel Management page**:

On the **Threat Feeds** tab of the `Threat Intel Management` page, click **Add Dataset**, and then define the filtration criteria to be applied to the feed data. For example, if you want to view only Phishing type feeds, then in the **Dataset Label** field, enter `IP Address`, and then in the `Filter Criteria` section, add the filter `Type Equals Phishing` and click **Save Dataset**:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-manage-datasets/release/1.0.0/docs/media/manageDatasets_threatIntelMngt.png" alt="Threat Intel Management page - Manage Datasets" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

Click the **View Dataset** icon to apply the filter and view only those feed records whose type is set as Phishing:

<img src="https://raw.githubusercontent.com/fortinet-fortisoar/widget-manage-datasets/release/1.0.0/docs/media/manageDatasets_createdDataSets.png" alt="Viewing saved datasets whose type is set as Phishing" style="border: 1px solid #A9A9A9; border-radius: 4px; padding: 10px; display: block; margin-left: auto; margin-right: auto;">

## Manage Datasets Settings

Provide the following details to customize the Manage Dataset widget to suit your requirements:

| Fields      | Description                              |
| ----------- | ---------------------------------------- |
| Title       | Specify the heading or title that you want to give to the datasets. |
| Data Source | Select the module from which you want to create datasets. For example, Threat Intel Feed. |

