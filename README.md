# SMART COSMOS Profiles Welcome Page Extension

This extension adds a Welcome Page and other static assets to SMART COSMOS Profiles.

To integrate this module into Profiles, add the following to your `objects.yml`:

```
serverExtensions:
  Welcome: net.smartcosmos.extension.smartcosmos.server.extension.welcome.profiles.WelcomeExtension


serverExtensionConfigurationPaths:
  Welcome: path/to/your/welcome-profiles.yml
```
