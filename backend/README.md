# Strapi (local development)
### Initial Setup (step 1): Create admin account
1. Install dependencies: `yarn install`
1. Start strapi cms: `yarn strapi develop`  
2. Goto http://localhost:1337/admin  and create an account
### Initial Setup (step 2): Set strapi API permissions
1. Left column: Click __Roles & Permissions__
2. Right side: For the entry __Public__, click the __pencil (edit) icon__
3. In the Permissions section under __Article__ *and* __Category__ select the following checkboxes: __find__ and __findone__
4. Top right of page: Click __Save__
### Initial Setup (step 3): Create at least one piece of content
1. Left column: Click __Articles__
2. Top right of page: Click the __+ Add New Article__ button
3. Fill out the form, make sure you choose a category
4. Click the __Save__ button.

*If the client is running, your content should now be visible at* http://localhost:3000

