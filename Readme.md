# How to Create a Checked ComboBox


<p>The following example shows how to create a checked combo box.</p>
<p>To enable this appearance, we set the editor's <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Editors.BaseEdit.StyleSettings.property"><u>StyleSettings</u></a> property to <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfEditorsCheckedComboBoxStyleSettingstopic"><u>CheckedComboBoxStyleSettings</u></a>:</p>


```xaml
<dxe:ComboBoxEdit.StyleSettings>
   <dxe:CheckedComboBoxStyleSettings />
</dxe:ComboBoxEdit.StyleSettings>
```


<p><strong>Note </strong>that a similar approach can be used to implement a radio button list. Use <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfEditorsRadioComboBoxStyleSettingstopic"><u>RadioComboBoxStyleSettings</u></a> as demonstrated in the <a href="https://www.devexpress.com/Support/Center/p/E1982">E1982: How to Apply Style Settings to the ComboBoxEdit</a> example.</p>

<br/>


