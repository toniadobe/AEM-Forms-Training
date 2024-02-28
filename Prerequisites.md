# AEM Forms Training Prerequisites


## Validate AEM Forms Provisioning

**Ensure you have a sandbox environment with AEM Forms enabled.**

  1. Log in to Cloud Manager and open your AEM as a Cloud Service instance.
  2. Click on "Edit Program" and navigate to the "Solutions & Add-ons" tab.
  3. Verify that AEM Forms is selected.
  4. Under "Sites," confirm that "Reference Demo" is the selected.

**If, AEM Forms is not listed:**

You will need to get it provisioned.

  1. You can request provisioning by contacting: <https://provisioninghub.corp.adobe.com/> (VPN required)
  2. For more information on Sandbox Provisioning, please refer to Bridget's XSC Enablement Playbook  [here](https://adobe-my.sharepoint.com/:o:/r/personal/bportela_adobe_com/Documents/XSC%20Enablement%20Ramp%20Playbook?d=wdbcfcd960e454bce87bda06ac133ec7a&csf=1&web=1&e=bucE1e).

## Enable AEM Forms on your CS sandbox

After enabling the Forms programing, you will need to run a non-production pipeline for AEM Forms to show up in your environment.

<https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/onboarding/journey/developers.html?lang=en>

## Prepare for deep dive training

### Verify ability to create App Registration in Azure

1. **Log in to:** <https://portal.azure.com/>
2. **Navigate to:** "App registrations" under Azure Services.
3. **Confirm:** You can access the App registrations page.

**Optional Step:**

**Follow:** Instructions to configure One Drive Cloud Service configuration in AEM Forms <https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/one-drive/store-form-submission-one-drive.html?lang=en>

### Obtain Adobe Sign Developer Account (Optional)

1. Obtain an Adobe Sign developer account. You will need to use a personal email address for this account, not your Adobe ID. <https://www.adobe.com/sign/developer-form.html>
2. Follow the instructions here, <https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/services/adobe-sign-integration-adaptive-forms.html?lang=en#adobe-acrobat-sign-for-government>, to configure Adobe Sign on you AEM as Cloud Service environment.
