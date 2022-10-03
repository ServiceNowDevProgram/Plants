# Contributing

## General requirements

- Pull request descriptions must be explicit and descriptive to what is being changed.
  - Changes that are not within the scope of the description will result in the entire PR being rejected
- Low effort/spam Pull Requests will be marked as spam accordingly.

## Ideas

See the Issues tab for parser ideas. Make sure to leave a comment on an issue if you're working on it.

## Process

1. Fork this repo
2. Go to your ServiceNow instance
3. Go to `System Applications` => `Studio`
4. Once Studio loads, select `Import From Source Control`
5. Use your forked repo to [Import your application](https://developer.servicenow.com/dev.do#!/learn/learning-plans/quebec/new_to_servicenow/app_store_learnv2_devenvironment_quebec_importing_an_application_from_source_control)
6. Make updates to the application
7. In Studio, commit your changes to source control
8. Submit a pull request to the ServiceNowNextExperience/hacktoberfest22-recipes
 `main` branch

## Plants are enough!

Along with new features, or any issues that appear in this repo's issues tab, we welcome you to simply submit a plant too!

1. Go to the recipe-db page on your instance (see above)
2. Submit a new recipe with a picture
3. Open the application in App Engine Studio (AES)
4. In the data section, click the preview button on the Recipe row
5. Check the checkbox next to the recipe record you added in the recipe list
6. Right click on the list header and choose "Create Application Files"
7. Choose "New install and upgrades" and select OK
8. Via AES or Studio, commit your changes and open a new Pull Request!
