---
name: phpcheck-server
description: Check PHP2Shell patch status with local or server access.
---

Check the PHP version serving the site. Start with `php -v`, but verify that
it matches the site's PHP-FPM or Apache installation.

Compare the version and full package revision with current PHP or vendor
security advisories. Vendor backports may fix an older version.

The running PHP build and the vendor's package advisory are the useful checks.
Configuration settings alone do not establish that PHP is patched.
Report the version, patch status, and any required update. If you cannot
verify the serving version, report unknown. Do not run exploit probes.
