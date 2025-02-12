# Microsoft Purview Information Protection/Mip C# 
Microsoft Purview Information Protection (formerly Microsoft Information Protection) to help you discover, classify, and protect sensitive information wherever it lives or travels(https://learn.microsoft.com/en-us/purview/information-protection)
## Console Application
#### The Quickstart is centered around building applications that use the MIP SDK libraries and APIs.
> [!NOTE]
> : Your application will always require a registered client application.<br>
> ref: [Register a client application with Microsoft Entra ID](https://learn.microsoft.com/en-us/information-protection/develop/setup-configure-mip#register-a-client-application-with-microsoft-entra-id)

<br> :thought_balloon:	Configure sensitivity labels
> Create your first sensitivity label. (https://learn.microsoft.com/en-us/purview/create-sensitivity-labels)
> 
> If you're currently using Azure Information Protection, you must migrate your labels to Office 365 Security and Compliance Center. For more information on the process, see [How to migrate Azure Information Protection labels to the Office 365 Security & Compliance Center.](https://learn.microsoft.com/en-us/azure/information-protection/configure-policy-migrate-labels)
<table aria-label="Table 1" class="table table-sm margin-top-none">
<thead>
<tr>
<th style="text-align: left;">Placeholder</th>
<th style="text-align: left;">Value</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">&lt;input-file-path&gt;</td>
<td style="text-align: left;">The full path to a test input file, for example: <code>c:\\Test\\Test.docx</code>.</td>
</tr>
<tr>
<td style="text-align: left;">&lt;label-id&gt;</td>
<td style="text-align: left;">A sensitivity label ID, copied from the console output in the previous Quickstart, for example: <code>f42a3342-8706-4288-bd31-ebb85995028z</code>.</td>
</tr>
<tr>
<td style="text-align: left;">&lt;output-file-path&gt;</td>
<td style="text-align: left;">The full path to the output file, which will be a labeled copy of the input file, for example: <code>c:\\Test\\Test_labeled.docx</code>.</td>
</tr>
</tbody>
</table>
<br>
<table aria-label="Table 1" class="table table-sm margin-top-none">
<thead>
<tr>
<th style="text-align: left;">Placeholder</th>
<th style="text-align: left;">Value</th>
<th style="text-align: left;">Example</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">&lt;application-id&gt;</td>
<td style="text-align: left;">The Microsoft Entra Application ID assigned to the application registered in "MIP SDK setup and configuration" (2 instances).</td>
<td style="text-align: left;">0edbblll-8773-44de-b87c-b8c6276d41eb</td>
</tr>
<tr>
<td style="text-align: left;">&lt;friendly-name&gt;</td>
<td style="text-align: left;">A user-defined friendly name for your application.</td>
<td style="text-align: left;">AppInitialization</td>
</tr>
<tr>
<td style="text-align: left;">&lt;Tenant-GUID&gt;</td>
<td style="text-align: left;">Tenant-ID for your Microsoft Entra tenant</td>
<td style="text-align: left;">TenantID</td>
</tr>
</tbody>
</table>
