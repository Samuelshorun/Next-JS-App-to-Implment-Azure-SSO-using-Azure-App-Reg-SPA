Integrate Next.js web app with Azure AD

#Register an Azure AD application.
#Implement a simple, Azure AD-integrated Next.js-based application.
#Validate the Azure AD integration of the Next.js-based application.

Clone App
Install git
Install Node Js
#############################################################


edit content of the ./src/authConfig.js file, replace the <client_ID> and <tenant_ID> placeholders with their respective values,

edit content of the ./src/authConfig.js file, replace the entry scopes: ["User.Read"] with scopes: ["User.Read"].

git clone https://github.com/Samuelshorun/NextApp\Next-JS-App-with-MSAL-to-Implement-Azure-SSO-using-Azure-App-Reg-SPA/m06u07




npm install
npm audit fix --force
npm run-script build
npm run-script start

###########################################
reference:
https://learn.microsoft.com/en-us/training/modules/cna-set-up-azure-ad-use-scale/7-exercise-integrate-next-js-web-app-azure-ad
