**ServerAnnouncer** A plugin that allows you to send a server wide message as the server with a custom prefix and color.

[BitBucket IssueTracker](https://bitbucket.org/austinv900/oxide-plugins/issues)

## Command
- `/say [message]` -- Broadcast message

## Configuration
You can configure the settings in the **ServerAnnouncer.json** file under the oxide/config directory.
```json
{
  "Server Chat Name": "[ServerConsole]"
}
```
## Localization
The default messages are in the ***ServerAnnouncer.en.json** under the oxide/lang directory. Language files are also available for French, German, Russian, and Spanish. To add support for another language, just copy one of the defaults, change the language code (en, fr, de, ru, or es), and then customize the messages.
```json
{
  "MessageFormat": "{0}: {1}",
  "NoAccess": "You are not allowed to use this command",
  "NoMessage": "You did not specify a message"
}
```
