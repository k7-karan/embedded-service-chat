<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKd0000052SO1',
				'BSC_Web_Deployment',
				'https://ac1730189866016.my.site.com/ESWBSCWebDeployment1730264897831',
				{
					scrt2URL: 'https://ac1730189866016.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ac1730189866016.my.site.com/ESWBSCWebDeployment1730264897831/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>