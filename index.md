<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DIp0000008aLO',
				'FR_MIAW_Bot_Web_Deployment',
				'https://one-jiobp--full.sandbox.my.site.com/ESWFRMIAWBotWebDeploy1717151051687',
				{
					scrt2URL: 'https://one-jiobp--full.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://one-jiobp--full.sandbox.my.site.com/ESWFRMIAWBotWebDeploy1717151051687/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
