# LocalSpoof downloads

Public signed downloads for LocalSpoof. Application source remains private.

Android works independently and can optionally be controlled by the Windows app over USB or Android authenticated wireless debugging. No LocalSpoof account or hosted user-data service is required.

Download an APK or Windows installer from Releases. Android installs in place using the original release certificate. Windows updates use a pinned Minisign publisher signature; this is separate from Windows Authenticode publisher certification. The catalog also has an original-publisher RSA signature.

After installing the first updater-enabled version, use Settings → Updates to check and install future published releases. Stop playback and finish mock-provider/radio cleanup before installation. Android can request install-source permission and confirmation. Updates do not start a journey automatically.

Online map, search and routing providers receive the requests users choose to make. GitHub may retain download request metadata; no journey, location history or LocalSpoof user account is uploaded to this repository.
