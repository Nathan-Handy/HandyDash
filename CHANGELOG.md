# Changelog

## v1.1

Version 1.1 includes the bug fixes listed below.

Please note: If you are already running HandyDash v1.0, simply backup your 'handydash-configuration.json' file, and copy this back into the wwwroot folder once v1.1 is extracted.

**Bug Fixes:**

- The warning message for upcoming intermediate and root certificate expiry, now correctly displays the certificate name.
- The error message for intermediate and root certificates that have expired, now correctly displays the certificate name.

## v1.0

Please see below for HandyDash v1.0 features.

**Available Checks**

- HTTP check for 200-299 (success) responses (follows 30X redirects).
- HTTP check for specific response content (text).
- HTTP check for latest and average response times.
- HTTP check for validity of server, intermediate, and root certificates.
- TCP check conducted (only) if HTTP check failure occurs.
- IP check conducted (only) if TCP check failure occurs.


**Warnings & Failures**

- Informative summary of HTTP, TCP, IP warnings and failures.
- Warning if HTTP response is slower than average by 100%.
- Warning if expiry date of server, intermediate, root certificate is less than 2 weeks, but more than 2 days.
- Error if expiry date of server, intermediate, root certificate is less than 2 days.
- Error if expiry date of server, intermediate, root certificate has passed, or start date is not yet reached.
- Error if server, intermediate, root certificate is invalid, including missing SAN values, or signed by an untrusted certificate authority.
- Error if HTTP response is not received within 15 seconds.
- Error if HTTP response is slower than average by 200%.
- Error if HTTP response code is not 200-299, or 30X redirect.
- Error if HTTP response does not contain the expected response content (text).
- Error if TCP check (connection) is not complete within 3 seconds. (Only executed when HTTP check fails).
- Error if IP check (ping response) is not received within 2 seconds. (Only executed when TCP check fails).
- Date and Time shown for the most recent failure ‘Last Failure’, when node is in the warning or failed state.
- Date and Time shown for the initial failure ‘First Failure’, when consecutive failures have occurred. ‘First Failure’ is reset upon node returning to a healthy state (green state).
- Date and Time shown for the most recent alert ‘Last Alert’, when node has returned to a healthy state (green state).
- Automatic bubble up of warning and failure states (yellow and red states), when 2 consecutive alerts have occurred for a given child node.
- Bubbled up alerts propagate to the root/top level node.
- Ability to suppress bubbled up alerts - at the source of the alert - for 24 hours.

**General**

- Browser based tree view UI, with in-built browser zoom options.
- Single click to zoom to any individual node (useful when browser zoom is set to a low value in order to display many nodes).
- Expand and collapse button for each parent node.
- UI options for spacing between parent and child nodes, and horizontal or vertical display of child nodes.
- Automatic polling of all HTTP targets at 1 minute intervals.
- Automatic refresh of browser UI at 1 minute intervals.
- HTTP check automatically follows 30X redirects and conducts checks against the target location.
- Logging of all failures to the console UI, containing local and UTC time that each failure occurred.
- Multi-threaded checks, ensuring slow response / failure of one node does not block the check of others.
- Runs on local URL http://127.0.0.1:55480/, with port configurable via “Urls” setting in appsettings.json.
- All monitor configurations are persisted to a single portable JSON file 'handydash-configuration.json', located under the wwwroot folder.
- Cross platform support, including Windows, Linux, and macOS (please enquire about further platforms).