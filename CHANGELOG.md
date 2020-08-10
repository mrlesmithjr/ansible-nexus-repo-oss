commit 2fa76b1ca28aacbd08ba56e35428f0c8a9108e8f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Aug 10 13:43:36 2020 -0400

    Added Flake8 config

commit 53e80c80d9ff52148a785d35fda38067a183db47
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Aug 10 13:31:36 2020 -0400

    Fixed linting issues

commit 21d086b09a0f908b03ad4b907917c7a2e26b951e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Aug 10 13:26:28 2020 -0400

    First commit of Complete refactoring of role
    
    This brings the latest version along with a ton of refactoring to make
    this role more feature rich going forward.

commit 8994b06a59f0dc8999bb96fe960033e3d8145528
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 01:57:27 2020 -0500

    Disabled Debian 10 testing
    
    - Need to figure out JRE package to install

commit 35a04bc8981999968dbdb51e5efa125ddb5fc1e8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 01:43:51 2020 -0500

    Changed Molecule scenarios, tests, etc.

commit 489c36b4c277350d4709ced97a3f8717991544c3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 01:43:39 2020 -0500

    Updated files, etc. after new structure

commit c47792f214fbbe51cfac772b1327f6783c58c9b8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 18:02:39 2020 -0500

    Changes needed based on new Molecule testing, etc.

commit 44527c228f0223c38860aa58a09f0f7a186e5f61
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 17:27:23 2020 -0500

    Added new files, etc. from Cookiecutter template

commit f683aae4d610c2b763296cba53a84b3c75810c07
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 17:27:02 2020 -0500

    Updated existing files based on Cookiecutter template

commit a7d19078203ef4b9d9e5090c7693efca49612515
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 17:26:45 2020 -0500

    Added new Molecule testing

commit c73c633e2f94f4d1a69342a9b18fff7fa82d3357
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 17:26:21 2020 -0500

    Removed no longer needed files

commit 79c984ab7b07d54dc3d273a73f6b0127ac858644
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jul 20 22:35:17 2019 -0400

    Added check for service availability/Changed admin pass vars
    
    - When nexus service starts, it takes a bit of time before the service
    is ready. Which also means, the very first time the service starts, the
    temp admin password is not available until the service is up and
    listening. So, we now wait for port 8081.

commit 140ab5bc794a092cf7912f38d8565ce43099420d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Jul 16 15:21:41 2019 -0400

    Added ability to define install dir for Linux
    
    - Improves installation location flexibility

commit 13c3cfceb4440776eb93c665de67f771b034272a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Jul 16 15:15:26 2019 -0400

    Updated method to determine path for admin.password
    
    - Improves method of locating admin.password rather than hard coding.

commit ec5db77d695e73bc5ad10d17198e0bdc2c0fa795
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Jul 16 15:06:08 2019 -0400

    Added initial Windows support
    
    - Improves installation options
    - Windows installation testing and validation needed still.

commit 2a6d725291b29b56c0951690526edd25f3c95761
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Jul 16 15:01:49 2019 -0400

    Finalized renaming repo and vars

commit 2a997b0a98dc5068850a16bfd6dc1eb06f5825d3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Jul 16 14:38:06 2019 -0400

    First commit
