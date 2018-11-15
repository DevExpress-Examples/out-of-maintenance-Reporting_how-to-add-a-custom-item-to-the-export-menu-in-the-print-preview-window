<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/CustomItem/Form1.cs) (VB: [Form1.vb](./VB/CustomItem/Form1.vb))
* [Program.cs](./CS/CustomItem/Program.cs) (VB: [Program.vb](./VB/CustomItem/Program.vb))
* [XtraReport1.cs](./CS/CustomItem/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/CustomItem/XtraReport1.vb))
<!-- default file list end -->
# How to add a custom item to the export menu in the Print Preview window


<p>Please handle the ReportPrintTool.PreviewForm.Shown event to get access to the drop-down control located on the toolbar. Then, it is necessary to add your own item to the items collection of the drop-down control. Also, you can use this approach to accomplish the same task in the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraPrintingPrintToolMembersTopicAll"><u>PrintTool.Preview</u></a> window.</p><br />


<br/>


