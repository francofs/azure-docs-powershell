---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: c2a3c653-fbba-4d24-bced-faea67c1d4a6
schema: 2.0.0
ms.assetid: 48B9D59D-FF51-4F70-9A29-FD017A9A8383
---

# Get-AzureVirtualNetworkGatewayKey

## SYNOPSIS
Gets the key for an azure_2 virtual network gateway.

## SYNTAX

```
Get-AzureVirtualNetworkGatewayKey [-GatewayId] <String> [-ConnectedEntityId] <String>
 [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVirtualNetworkGatewayKey** cmdlet gets the key for an azure_2 virtual network gateway.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -ConnectedEntityId
Specifies the ID of a connected entity.

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

### -GatewayId
Specifies the ID of a gateway.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
ps_azureprofile_description

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Reset-AzureVirtualNetworkGatewayKey](.\Reset-AzureVirtualNetworkGatewayKey.md)

[Set-AzureVirtualNetworkGatewayKey](.\Set-AzureVirtualNetworkGatewayKey.md)

