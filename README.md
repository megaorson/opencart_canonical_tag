# opencart_canonical_tag
# This plugin will add new field to product form (add\edit) . This field is a canonical tag who will add to <head>
# For more information about this tag go to https://support.google.com/webmasters/answer/139066
# Installing:
# 1.Navigate to Extensions -> Extensions installer.
# 2.Choice the file canonical.ocmod.zip and upload
# 3.Go to the template "catalog/view/theme/YourTheme/template/common/header.tpl" and add next line
# <?php if ($canonical) { ?>
# <link rel="canonical" href="<?php echo $canonical; ?>" /> 
# <?php } ?>