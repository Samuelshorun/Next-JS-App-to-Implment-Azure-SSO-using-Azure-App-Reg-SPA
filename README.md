Integrate Next.js web app with Azure AD

#Register an Azure AD application.<br />
#Implement a simple, Azure AD-integrated Next.js-based application.<br />
#Validate the Azure AD integration of the Next.js-based application.<br />

Clone App<br />
Install git<br />
Install Node Js <br />

<br />
#############################################################
<br /><br /><br />

edit content of the ./src/authConfig.js file, replace the <client_ID> and <tenant_ID> placeholders with their respective values,
<br />
edit content of the ./src/authConfig.js file, replace the entry scopes: ["User.Read"] with scopes: ["User.Read"].
<br />
git clone https://github.com/Samuelshorun/NextApp\Next-JS-App-with-MSAL-to-Implement-Azure-SSO-using-Azure-App-Reg-SPA/m06u07


<br /><br />

npm install <br />
npm audit fix --force <br />
npm run-script build <br />
npm run-script start <br />

###########################################
<br />
reference:
<br />
https://learn.microsoft.com/en-us/training/modules/cna-set-up-azure-ad-use-scale/7-exercise-integrate-next-js-web-app-azure-ad

<br />
<br />
https://github.com/MicrosoftDocs/mslearn-cloud-native-apps.git