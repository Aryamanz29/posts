---
title: "OpenWisp'22 Release Sprint 🚀"
date: "2022-02-18T17:58:10Z"
draft: false
pin: true  <!--Do you want to pin this blog post? (true/false)-->
summary: OpenWisp'22 Release Sprint <!--Blog post visible summary here-->
--- 
<!--Blog content-->

![o-sprint](https://user-images.githubusercontent.com/56113566/154739652-d72ca1ef-c67f-4822-be90-666fcb5681cc.jpeg)

From last one week, Me and other fellow contributors were participating in [OpenWisp'22](https://openwisp.org/) release sprint, Today It finally came to an end. It was a very new experience for me because I got the opportunity to learn about how actually maintainers of big open-source project reviews contributors PR's and what they're actually wanted from contributors to do before they request review from maintainers. I'll mention some valuable points which I've noted during this sprint, and they are very useful for new contributors.

- **Read documentation** : Before diving into an issue section, I would always suggest everyone to read documentation first, In [OpenWisp](https://openwisp.org/) you found every project is well documented. Not only you're going to understand how the project is working (technical aspect), but you'll also get an idea about motivation of the project i.e. why it started, what real world problem it tries to solve, What it's going to achieve in future etc.

- **Code is not always right** : You always think that if I solve this issue or that issue, my PR's easily get merged into projects, but this is not a good practice when it comes to contributing to big projects. Project maintainers said, _We humans are generally more likely inclined towards text that talks around changes we made rather than looking actual code/implementation every time._ This means, let say If today I created a PR for implementing feature Y, and I just simply write code without having a good commit message (not having clear explanation about my changes) then it might not be creating any concern today but in future these small things will raise some serious issues, and then we can't figure out its solution.

- **Test driven development** :  Google says, _Test-driven development is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases._ So whenever you're solving bugs don't forgot to write tests for that and remember if you remove your patch from code that particular test case must fail to justify your change & the test case must be specific to your patch.

- **Double Check Double Check** : Do you remember your high school exams? You also re-check everything before submission, Same practice we are applying here while submitting PR's for maintainers & do always remember to double-check your work and try to run for different cases, That's not only saves your time but also maintainers as well.

- **Be patient** : Always remember, open-source contribution is a game of checking your level of patience. Do your work and make sure you follow above mention steps, thoroughly read project contributing guidelines, then just leave your PR for maintainers review (You may also ping them on their IRC channel if you want).

Maintainers are also wanted to check your work and suggest you changes if required, but you need to be patient for that, or You may start looking for some other issues during that time gap,  At last I would say just don't sit idle, If you really want to contribute and learn new things from the community. 😄


My links of PR's that got reviewed and merged during sprint mention below 👇

  - https://github.com/openwisp/openwisp2-docs/pull/150
  - https://github.com/openwisp/openwisp-firmware-upgrader/pull/175
  - https://github.com/openwisp/openwisp-utils/pull/277
  - https://github.com/openwisp/openwisp-network-topology/pull/134
  - https://github.com/openwisp/openwisp-notifications/pull/220
  - https://github.com/openwisp/openwisp-radius/pull/372
  - https://github.com/openwisp/openwisp-users/pull/305
  - https://github.com/openwisp/openwisp-users/pull/304
  - https://github.com/openwisp/openwisp-utils/pull/276
  - https://github.com/openwisp/openwisp-monitoring/pull/342
  - https://github.com/openwisp/openwisp-notifications/pull/220
  - https://github.com/openwisp/openwisp-firmware-upgrader/pull/175
  - https://github.com/openwisp/openwisp-radius/pull/381
  - https://github.com/openwisp/openwisp-users/pull/306
  - https://github.com/openwisp/openwisp-controller/pull/596

Keep learning, Stay healthy 🙃 

