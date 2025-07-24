We will create a swiss-army-knife desktop app for developers called "NewDevToys". The app will consist in a set of tiny tools designed to help developer sin their daily life by allowing to do tasks such as format a JSON or decode some Base64.

The app will have a navigation view using WinUI3 and XAML that list all the tools in categories. The content area will display the selected tools. There should be an "All tools" item in the navigation view that will allow to display every tools and navigate to them. For each tools, user generally needs to enter some input, and some read-only output will be displayed. The output should be copiable and savable on the hard drive using buttons.

Make sure to create a reusable API to limit the amount of duplicated code. Use Dependency Injection to help with it. Leverage Microsoft Learn documentation for best practices.

Here is the list of tools I want you to create in the app:
Converters
 JSON <> YAML
 Number Base
Text
 Escape / Unescape
 Analyzer & Utilities
Encoders / Decoders
 Base64 Image
 Base64 Text
 HTML
 QR Code
 URL
Formatters
 JSON
 XML
Generators
 Hash / Checksum
 Lorem Ipsum
 Password
 UUID

For each tool:
- Create a mock up UI
- Create unit tests for each tools and for the app in general.

Please find some screenshot from an existing app for inspiration on the UI.

Your first step will be to write a detailed spec that an AI will then use to build the project, and save it into a file. Split the work into small milestones.

-------------------------
Cool, now please go-ahead and apply the specification.
- Again, leverage online documentation for best practice.
- For every milestone in your work, create some unit tests. Build, and run them. Once they all pass, then git commit the changes, and continue to the next milestone.