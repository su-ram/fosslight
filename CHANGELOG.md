# Changelog

## v1.2.6 (17/09/2021)
## Changes
## 🚀 Features

- Update warning message condition @FOSSLight-dev (#132)
- Add function to save NVD Feed Data from 2002 @FOSSLight-dev (#118)
- Search website regardless of http://, https://, www. @doggai10 (#114)

## 🔧 Maintenance
- Add alert when the number of OSS versions is 1 @riyenas0925 (#123)
- Add line separator between notice intro and OSS list @wkdalsgh192 (#121)
- Add user guide and restriction to license popup @riyenas0925 (#125)

## 🐛 Hotfixes

- Update Oss Sync Function @FOSSLight-dev (#117)

---

## v1.2.5 (09/09/2021)
## Changes
## 🚀 Features

- Recommend the OSS Name according to the OSS Naming Rule @namkyu1999 (#82)

## 🐛 Hotfixes

- Update OSS Sync Function @FOSSLight-dev (#117)
- Exclude from 'Check OSS Name' unless it is an 'Unconfirmed open source' @soimkim (#116)

## 🔧 Maintenance

- Delete "Need check" in the Obligation Type from the search box in the License List @Lee-JaeHyuk (#101)
- Translate some korean comments to english @wkdalsgh192 (#60)

---

## v1.2.4 (03/09/2021)
## Changes
## 🚀 Features

- 3rd party / project status check func & oss sync func @FOSSLight-dev (#113)
- Add Docker mailserver in docker-compose @epicarts (#112)
- Add license information display when clicking the Restriction icon @riyenas0925 (#71)
- Expose a save button for a creator, watcher, and admin @astrod (#88)

## 🐛 Hotfixes

- 3rd party/project status check function @FOSSLight-dev (#115)
- 3rd party / project status check func & oss sync func @FOSSLight-dev (#113)

## 🔧 Maintenance

- Fix hide 'Check OSS Name' button from unrelated users @hyewoncc (#110)
- Modify pop-up phrases that occur when you press the reopen button @suhwan-cheon (#97)
- Rename 'Excel Download' Button to 'Export' @sw-develop (#104)
- Drop button requires comment @soimkim (#105)

---

## v1.2.3 (27/08/2021)
## Changes
## 🚀 Features

- Add a new function to synchronize from OSS information @FOSSLight-dev (#93)

## 🐛 Hotfixes

- Add a new function to synchronize from OSS information @FOSSLight-dev (#93)

## 🔧 Maintenance

- Modify 'Request Review' button(Delete icon and rename to 'Request') @ubermen5che (#91)
- Fix header column names of Vulnerability Log table @kimtaehyun98 (#87)
- Fix typo 'SourceCode' in Self-Check @hyewoncc (#83)
- Add label:improvement to also appear as child of Feature in release draft @riyenas0925 (#81)
- Modify github action to deploy 30 seconds after release @soimkim (#76)

---

## v1.2.2 (20/08/2021)
## Changes
## 🚀 Features

- Add deactivate function to OSS @FOSSLight-dev (#72)
- Add a function to check details detected license. @ubermen5che (#69)
- Add CVE link to vulnerability discovered mail body (#64) @acafela (#66)
- Add License Type option for OSS List search @hyewoncc (#62)

## 🐛 Hotfixes

- Add deactivate function to OSS @FOSSLight-dev (#72)
- Fix a bug for type check error. @ubermen5che (#61)

## 🔧 Maintenance

- Fix toggle button color to match others @hyewoncc (#73)
- Change Admin can Restart/Complete with no comment @kimtaehyun98 (#63)
- Update message.properties @k2heart (#65)
- Deploy the latest release to demo.fosslight.org @soimkim (#68)
- Add auto-updating CHANGELOG.md on develop branch @riyenas0925 (#58)

---

## v1.2.1 (13/08/2021)
## Changes
- Add to show docker-compose log in github-actions @riyenas0925 (#50)

## 🚀 Features

- Bug fix - validation check @FOSSLight-dev (#27)

## 🐛 Hotfixes

- Update the function related to detected license and changing status @soimkim (#56)
- Add DROP status to project search @riyenas0925 (#45)
- Bug fix - validation check @FOSSLight-dev (#27)
- Remove warning message @riyenas0925 (#25)
- Fix a bug related to load properties @soimkim (#22)
- Fix a bug to create directories @soimkim (#17)

## 🔧 Maintenance

- Update the function related to detected license and changing status @soimkim (#56)
- Move the Drop button to the right of the Delete button in "Project > Basic Information" @suhwan-cheon (#55)
- FIx typo 'website' in UI @epicarts (#48)
- Fix Timezone to Asia/Seoul @epicarts (#46)
- Typo in Class @kimtaehyun98 (#41)
- Fix gradew file permission @epicarts (#38)
- Fix typo in CoTopComponent.java in fosslight @ubermen5che (#34)
- Fix Typo @greeenly (#32)
- Update .gitignore to ignore personal data folders @namkyu1999 (#31)
- Change db settings for running with Docker @soimkim (#24)
- Run PR action for all branches @soimkim (#23)

---

## v1.2.0 (30/07/2021)
## Changes
## 🚀 Features

- Add Declared/Detected License to OSS @soimkim (#14)

## 🐛 Hotfixes

- Fix a bug - Vulnerability score of Self-Check List @soimkim (#14)

## 🔧 Maintenance

- Change 3rd Party List - Searching UI @soimkim (#14)
- Add a spring boot badge to README @soimkim (#12)
- Add Description of ID and Password for Demo site @fu7mu4 (#10)

---

## v1.1.0 (22/07/2021)
## Changes
## 🚀 Features

- Improve project-related functions @FOSSLight-dev (#6)
- Created Dockerfile and docker-compose.yml @sameer1046 (#3)

## 🐛 Hotfixes

- Improve project-related functions @FOSSLight-dev (#6)
- Move DB related files to db directory @soimkim (#5)

## 🔧 Maintenance

- Add action for PR @soimkim (#9)
- Move DB related files to db directory @soimkim (#5)
- Update docker files @soimkim (#4)
- Remove unnecessary files @soimkim (#1)

---

## v1.0.1 (27/05/2021)
## Changes
* Set up automated deployment.

---

## v1.0 (30/04/2021)
Release FOSSLight v1.0 🎉