Create a static web app

    1. Now that the repository is created, you can create a static web app from the Azure portal.

      Go to the Azure portal.
      Select Create a Resource.
      Search for Static Web Apps.
      Select Static Web Apps.
      Select Create.

    2. In the Basics section, begin by configuring your new app and linking it to a GitHub repository.

    3. If necessary sign in with GitHub, and enter the following repository information.
    	Setting 	Value
    	Organization 	Select your organization.
	    Repository 	Select my-first-web-static-app.
	    Branch 		Select main.
    4. In the Build Details section, add configuration details specific to your preferred front-end framework.
      From the Build Presets dropdown, select Custom.
      In the App location box, enter ./src.
      Leave the Api location box empty.
      In the Output location box, enter ./src.

    5. Select Review + create.

    6. Select Create
