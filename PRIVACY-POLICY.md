# Privacy Policy

**Publisher:** Dr. Matt Booth, publishing as [thatosxguy](https://github.com/thatosxguy)

**Contact:** [admin@strixmcs.com](mailto:admin@strixmcs.com)

**Last updated:** October 7, 2026

## Scope

This policy explains how I handle personal information in connection with the GitHub repositories, software releases, documentation, project pages, and support channels that link to this policy. “I” and “my” refer to Dr. Matt Booth.

A project's own privacy notice describes its particular storage and network behavior. Read that notice alongside this policy, especially before enabling an online service. The FanFic to Audio details below describe version 1.3.0; other projects and versions may work differently.

GitHub operates the platform that hosts my account and repositories. GitHub's collection and use of information are covered by the [GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). This policy covers my handling of information, rather than GitHub's operations or unrelated websites.

## Information I receive

You may provide information when you email me, open an issue, join a discussion, submit a pull request, or report a security problem. This can include your name or GitHub username, email address, message contents, attachments, and technical details you choose to share, such as an app version, operating system, error message, or diagnostic log.

Public GitHub contributions are visible to other people. Private email and private security reports are handled through their respective service providers. Email providers may also process routing, delivery, and security information associated with a message.

GitHub separately collects information such as IP addresses, device and browser details, and website activity. It may make repository traffic statistics available to maintainers. Visiting a GitHub page or downloading a release does not give me access to the files, credentials, or settings on your device.

## How I use information

I use information provided to me to:

- Respond to questions and support requests.
- Investigate bugs, reproduce problems, and improve projects.
- Review contributions and maintain project documentation.
- Investigate security reports, prevent abuse, and protect project users.
- Meet applicable legal obligations and address disputes.

I do not sell personal information, use support information for advertising, or share it for cross-context behavioral advertising. I do not add people who contact me to a marketing mailing list without their permission.

Where applicable data protection law requires a legal basis, handling an ordinary support request or contribution is generally based on legitimate interests in communicating with users and maintaining the project, subject to those users' rights. A separate agreement, legal obligation, or consent may provide the basis for other processing where appropriate. Optional app features and data sent to third-party services are described below and in each project's notice.

## FanFic to Audio: data on your Mac

FanFic to Audio 1.3.0 has no application analytics or telemetry implementation and no developer-operated backend. It does not automatically send your EPUBs, audio, app preferences, or API keys to me.

| Data | Storage and purpose |
| --- | --- |
| EPUBs, combined series, audiobooks, and book-update backups | Local folders you choose, or backups beside an updated book. |
| App preferences | macOS preferences, including paths and narration settings. Provider API keys and the contents of your configuration file are not stored there. |
| Provider API keys | macOS Keychain, when you explicitly select **Save Key**. **Remove Key** deletes the selected provider's saved key. Keys are used to authenticate requests to that provider. |
| Audiobook queue and narration presets | `~/Library/Application Support/FanFicToAudio`, so the queue and settings survive restarts. These records can contain book titles, authors, local paths, and narration settings, but not API keys. |
| AI usage estimates | Local counts, estimated costs, and related usage records. These records do not contain book passages or credentials. |
| Resume checkpoints | Generated narration passages and validation information in the app's `Checkpoints` folder. These enable interrupted conversions to resume. |
| FanFicFare configuration | Your selected `personal.ini` and related files remain under your control. They may contain site credentials, cookie-file paths, proxy settings, or other service settings. |

macOS narration and audio encoding run locally. Downloading additional system voices or using operating-system services may involve Apple's own services and policies. Files stored in folders synced or backed up by another service are subject to that service's handling as well.

See [FanFic to Audio's detailed data-handling notice](https://github.com/thatosxguy/FanFictoAudio/blob/main/PRIVACY.md) for temporary files, caches, checkpoint cleanup, and additional technical details.

## Websites and optional AI narration

When you download or update a story, preview its metadata, or extract story links, FanFicFare contacts the selected website and related resources. Site authentication or services configured in your FanFicFare configuration may be used. Those websites and services receive the requests and are responsible for their own handling of information.

When you choose OpenAI or ElevenLabs for a narration preview or audiobook conversion, the app sends the selected book passages and narration settings to that provider over HTTPS, using your API key. OpenAI requests can also include narration instructions. Loading your ElevenLabs voice list contacts ElevenLabs using your key without sending book passages.

These requests go directly to the selected provider. Provider account terms, privacy practices, and data controls determine how that provider handles requests, generated audio, retention, and any permitted model improvement. Retention periods and model-improvement options can vary by provider, account configuration, and agreement.

Before using an AI service, review its current information:

- [OpenAI API data controls](https://developers.openai.com/api/docs/guides/your-data) and [Services Agreement](https://openai.com/policies/services-agreement/).
- [ElevenLabs Privacy Policy](https://elevenlabs.io/privacy-policy) and [Terms of Service](https://elevenlabs.io/terms-of-use).
- [GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) for repository and website use.

You can use local macOS narration instead of an AI provider. Cancelling a request cannot retract content already delivered to a provider. Retrying an unfinished passage may send it again.

## Sharing and public reports

Hosting and email providers process information needed to deliver their services. Project maintainers may access reports or contributions to investigate an issue or review a change. Public issues, discussions, and contributions can be copied, indexed, forked, or archived by others.

I may disclose information when required by law or when reasonably necessary to address a security incident, protect legal rights, or prevent abuse. I will use redacted or synthetic examples where practical when explaining a private report publicly.

Please do not put API keys, passwords, cookies, private configuration files, sensitive logs, or private books in a public issue. Review attachments and file paths before submitting them. For FanFic to Audio security problems, use [private vulnerability reporting](https://github.com/thatosxguy/FanFictoAudio/security/advisories/new) or email me.

## Retention and deletion

I retain support correspondence and private reports for as long as reasonably needed to respond, follow up, maintain security, and resolve related issues. Some records may need to be kept longer for legal obligations or disputes. You can contact me to request deletion of information I hold about you.

Public repository history and contributions may remain available as part of the project's development record. Removing information from a repository does not necessarily remove copies in forks, search indexes, archives, or other people's devices.

You control local app data. In FanFic to Audio, matching resume checkpoints are removed after a successful export; removing a queue item or selecting **Discard Saved Passages** removes that job's saved passages. Other checkpoints can remain until you delete them. Removing the app itself does not remove saved keys, preferences, queue records, checkpoints, EPUBs, audio, or backups. Use the app's key-removal controls and macOS tools to manage those records. I cannot remotely delete data on your Mac or in your third-party accounts.

## Your choices and rights

You can limit the information you share, choose local narration, remove saved provider keys, delete local files, and manage third-party privacy settings. To request access to, correction of, or deletion of personal information I hold, email [admin@strixmcs.com](mailto:admin@strixmcs.com). Depending on applicable law, you may also have rights to object to or restrict processing, obtain a portable copy, withdraw consent where processing relies on consent, or complain to a data protection authority. I will handle requests as required by applicable law and may ask for enough information to verify the request without requesting unnecessary sensitive data.

For information controlled by GitHub, an AI provider, a story website, or your backup service, contact that service directly. These services and email providers may process information in countries outside your own; consult their policies and account agreements for locations and safeguards.

## Security and children

No method of storage or transmission can guarantee complete security. Protect your Mac and provider accounts, and report suspected exposure of credentials promptly. A privacy request never requires you to email me an API key or password.

These project support channels are not intended to solicit personal information from children under 13. If you believe a child has sent me personal information, contact me so I can address it. Third-party services have their own age and account requirements.

## Policy changes and contact

I will publish changes here and update the date above. Material changes to a project's data handling will also be described in its documentation or release notes. A policy update does not automatically enable a new feature or authorize disclosure of existing private information for an unrelated purpose.

**Dr. Matt Booth**

GitHub: [thatosxguy](https://github.com/thatosxguy)

Email: [admin@strixmcs.com](mailto:admin@strixmcs.com)
