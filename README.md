# opencart canonical tag
 This plugin will add new field to product form (add\edit) . This field is a canonical tag who will add to head
 For more information about this tag go to https://support.google.com/webmasters/answer/139066
# Installing:
<ul>
 <li>Navigate to Extensions -> Extensions installer.</li>
 <li>Choice the file canonical.ocmod.zip and upload</li>
 <li>Go to the template "catalog/view/theme/YourTheme/template/common/header.tpl" and add next line</li>
 <li>	&lt;?php if ($canonical) { ?&gt;&lt;link rel="canonical" href="&lt;?php echo $canonical; ?&gt;" /&gt; &lt;?php } ?&gt;</li>
</ul>
# License - free
