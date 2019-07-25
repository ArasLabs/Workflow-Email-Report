# Workflow Report Server Email

The Workflow Report Server Email project adds a server-side version of the standard Workflow Report and an email template to allow this report to be attached to a server event such as a workflow assignment.

#### How it works
?

## History

Release | Notes
--------|--------
[v1.0.0] | First release 

#### Supported Aras Versions

Project | Aras
--------|------
[v1.0.0] | 11.15, 12.0+ 

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. Workflow Report Email import package
4. Aras set up to send emails (see documentation)

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\Workflow-Report-Email\Imports\imports.mf` file in the Manifest File field.
6. Select **???** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

You are now ready to login to Aras and try out Automatic Workflow Assignments.

## Usage

1. Log in to Aras as admin.
2. 

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Original Aras community project written by Sam Poe at Aras Corp. @sampoearas

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
