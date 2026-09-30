# Droid Agent — Privacy Policy

**Effective date:** 30 September 2026\
**App:** Droid Agent (package name: `com.droidagent.droid_agent`)\
**Developer:** Digital Stream\
**Contact:** digitalstream04@gmail.com

---

## 1. Summary

Droid Agent is an AI assistant that can act on your phone. It has no servers
and no user accounts. **The developer does not collect, receive, sell or share
any of your data.**

Everything you create in the app stays on your phone. The only data that
leaves the device goes directly from your phone to services that you choose
and configure yourself, such as the AI provider whose API key you enter.

## 2. What the developer collects

**Nothing.** Droid Agent does not include:

- analytics or usage tracking
- crash reporting
- advertising or advertising identifiers
- any server operated by the developer

## 3. Data stored on your device

The app stores the following in its private storage on your phone:

- **API profiles:** provider name, endpoint URL, model name, and your API key.
  API keys are kept in encrypted storage protected by the Android Keystore.
- **Conversations:** your messages, the AI's replies, and the results of the
  actions the agent ran.
- **Skills, agents and scheduled tasks** that you create or edit.
- **App settings.**

The app turns off Android cloud backup and device-to-device transfer, so this
data is not copied to Google Drive or to another phone.

To delete this data:

- delete conversations, skills and scheduled tasks inside the app;
- delete an API profile in Settings, which also deletes its API key;
- or clear the app's storage in Android Settings, or uninstall the app. This
  removes everything.

## 4. Data sent to third parties that you choose

### a) Your AI provider

To answer you, the app sends your conversation to the AI provider you set up,
over an encrypted HTTPS connection, using your own API key. Supported providers
include OpenAI, Anthropic, Google Gemini, OpenRouter, and any OpenAI-compatible
endpoint you enter, including one on your own computer.

What is sent can include:

- the text of your messages;
- files and images that you attach;
- results of actions the agent ran. Depending on the tools used, these can
  include text read from the screen, screenshots, file contents, command
  output, clipboard text and basic device information (for example model,
  Android version and battery level).

The developer never receives this data. How the provider stores and uses it is
governed by that provider's own privacy policy and terms. Please review them
before you use a provider.

### b) Web searches and web pages the agent opens

When a task needs it, the agent can search the web and fetch web pages.
Searches are sent directly from your phone to DuckDuckGo
([privacy policy](https://duckduckgo.com/privacy)), which receives the search
words and your device's IP address. Each website the agent opens also sees your
device's IP address, as with any browser request. No API key or account is used
for searching.

### c) Voice input

If you use the microphone button, speech is converted to text by your phone's
speech recognition service (usually provided by Google). Droid Agent does not
record or store audio. Only the recognised text is put in the message box.

## 5. Permissions and why they are used

Each permission is used only for the feature described. Most are optional, and
you can turn them off at any time in Android Settings.

| Permission | Why it is used |
|---|---|
| Internet | To talk to your AI provider, and to search the web and fetch web pages when a task needs it. |
| All files access, or photos, videos and audio | So the agent can find, read and organise files on your phone when you ask it to. Files are sent to the AI provider only when a task needs their contents. |
| Microphone | For voice input only, and only after you tap the microphone button. |
| Notifications | To show task progress, results, and approval requests. |
| Display over other apps | For a small floating robot that shows when the agent is controlling another app. Tapping it stops the agent. |
| Exact alarms, run at startup, ignore battery optimisation, foreground service and wake lock | So tasks you schedule run on time, including after a restart, and are not stopped by the system partway through. |
| Shizuku and Termux (optional apps you install yourself) | These give the agent a shell so it can read the screen, tap, type, open apps, and run commands and tools. The agent uses them only to carry out tasks you ask for. |

## 6. You stay in control

- The agent acts only on your request, or on a schedule you created.
- Sending a text message, placing a call, or creating a scheduled task
  **always asks for your confirmation first**, whatever approval mode you
  choose.
- You can stop the agent at any time with the floating robot or the stop
  button.
- Other actions follow the approval mode you pick. Before choosing a mode that
  lets actions run without asking, make sure you are comfortable with what the
  agent may do.

## 7. Children

Droid Agent is not directed at children under 13, and it does not knowingly
collect information from children. As explained above, the developer collects
no personal data from anyone.

## 8. Security

API keys are encrypted with the Android Keystore. Connections to AI providers
use HTTPS, unless you enter a plain `http://` address yourself, for example a
server on your local network. Your data is protected by your phone's own
security, so keep a screen lock enabled.

## 9. Changes to this policy

If this policy changes, the new version will be published at this address with
a new effective date. Significant changes will also be noted in the app's
release notes.

## 10. Contact

For questions about this policy or your privacy, contact:\
Digital Stream — digitalstream04@gmail.com
