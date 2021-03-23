# Authorized Buyers Ad Exchange API DotNet Samples
These samples demonstrate basic usage of the Authorized Buyers Ad Exchange API.

The Authorized Buyers Ad Exchange API DotNet Client Library makes it easier to
write .NET clients to programmatically access Authorized Buyer accounts.
The complete documentation for the Authorized Buyers Ad Exchange API docs are
available from <https://developers.google.com/authorized-buyers/apis/>.

## Features

- .NET Framework 4.5+
- .NET Standard 1.3 and .NET Standard 2.0; providing .NET Core support.

The code examples have been compiled for .NET SDK 4.5.2, .NET Core App 3.1, .NET 5.0.

## Announcements and updates

For API and client library updates and news, please follow the Google Ads Developers blog: <http://googleadsdeveloper.blogspot.com/>.

For questions and support look at our forum page: <https://groups.google.com/forum/#!forum/authorized-buyers-api>.

## Running the examples

### Download the repository contents

To download the contents of the repository, you can use the command

```
git clone https://github.com/googleads/googleads-adxbuyer-examples
```

or browse to <https://github.com/googleads/googleads-adxbuyer-examples> and
 download a zip.

### Setup Security
The API uses OAuth2 for security, you can read about the options for connecting
 at <https://developers.google.com/accounts/docs/OAuth2>

We will focus on using a Service Account; samples are included for prompting
 the user and using a refresh token

If you don't already have a Service Account and corresponding JSON key file

 * Launch the Google Developers Console <https://console.developers.google.com>
 * Click the **API Manager** item on the navigation menu.
 * Click **Credentials** menu option.
 * Click the link titled **Manage service accounts**.
 * You should now see a table listing the Service Accounts associated with the
  current project. Find the Service Account you had been using previously, and
  open the menu.
 * Select the **Create key** menu item.
 * Click the **JSON** key type option and click **CREATE**.
 * Set the path to the downloaded JSON file as the **ServiceKeyFilePath** value
  in **ExamplesConfig.cs**.

### Dependancies
The DoubleClick Ad Exchange Buyer API .Net Client Library is hosted on nuget.org

If nuget is configured you can skip to **Run the examples** and it will 
 automatically download the required libraries

Otherwise you can locate the client library at
 <https://www.nuget.org/packages?q=Google.Apis.adexchangebuyer&prerelease=true&sortOrder=relevance>

### Run the examples
When you are ready, hit F5

By default this will print out a usage method and show how to run a paricular example

If you know which example you want to run you may choose to set
Project|Properties|Startup Object and then hit F5

**Note:** Some of the examples need parameters configured for them to work, those parameters appear in the first few lines of the Run method in each case.

