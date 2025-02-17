# Export-IamJsonSpec

## Synopsis

Create JSON specification for Identity and Access Management.

## Syntax

```powershell
Export-IamJsonSpec [-workbook] <String> [-jsonFile] <String> [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

## Description

The `Export-IamJsonSpec` cmdlet creates the JSON specification file using the Planning and Preparation Workbook to deploy the Identity and Access Management for VMware Cloud Foundation validated solution:

- Validates that the Planning and Preparation is available
- Generates the JSON specification file using the Planning and Preparation workbook

## Examples

### Example 1

```powershell
Export-IamJsonSpec -workbook .\pnp-workbook.xlsx -jsonFile .\iamDeploySpec.json
```

This example creates a JSON specification for Identity and Access Management using the Planning and Preparation Workbook.

## Parameters

### -workbook

The path to the Planning and Preparation Workbook (.xlsx) file.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -jsonFile

The path to the JSON specification file to be created.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProgressAction

Progress Action

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: proga

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### Common Parameters

This cmdlet supports the common parameters: `-Debug`, `-ErrorAction`, `-ErrorVariable`, `-InformationAction`, `-InformationVariable`, `-OutVariable`, `-OutBuffer`, `-PipelineVariable`, `-Verbose`, `-WarningAction`, and `-WarningVariable`. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).
