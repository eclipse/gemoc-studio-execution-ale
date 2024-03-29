# Changelog

## v3.6.0 (06/04/2023)

#### Enhancements:

- [**enhancement**]  Manage step return values and step parameters  [#57](https://github.com/eclipse/gemoc-studio-execution-ale/pull/57)

#### Bug Fixes:

- [**bug**] Bump to version of k3 including StepCommand return null fix [#59](https://github.com/eclipse/gemoc-studio-execution-ale/pull/59)
- [**bug**] Fix: remove self from step parameters [#58](https://github.com/eclipse/gemoc-studio-execution-ale/pull/58)

#### Version upgrades

- [**bump**] Bump to Eclipse 2022-06 [#55](https://github.com/eclipse/gemoc-studio-execution-ale/pull/55)

---

## v3.5.0 (30/06/2022)

#### Enhancements:

- [**enhancement**]  Manage step return values and step parameters  [#57](https://github.com/eclipse/gemoc-studio-execution-ale/pull/57)
- [**enhancement**] Initial version of a Webprotocol based EngineAddon server [#54](https://github.com/eclipse/gemoc-studio-execution-ale/pull/54)
- [**bug**][**enhancement**] Improve management of ALE when  used as SiriusInterpreter [#45](https://github.com/eclipse/gemoc-studio-execution-ale/pull/45)
- [**enhancement**] Use general extension point [#25](https://github.com/eclipse/gemoc-studio-execution-ale/pull/25)
- [**enhancement**] Improve default Engine addon launch conf tab [#27](https://github.com/eclipse/gemoc-studio-execution-ale/pull/27)
- [**enhancement**] Validation plug-in for the Ale meta-programming approach in GEMOC Studio [#34](https://github.com/eclipse/gemoc-studio-execution-ale/pull/34)
- [**enhancement**] "metaprog" entry added to dsl files for the Ale example [#35](https://github.com/eclipse/gemoc-studio-execution-ale/pull/35)
- [**enhancement**] Metaprogramming approach name changed to FullyQualifiedName [#36](https://github.com/eclipse/gemoc-studio-execution-ale/pull/36)
- [**enhancement**] Example's metaprog entry fixed [#37](https://github.com/eclipse/gemoc-studio-execution-ale/pull/37)
- [**enhancement**] Metaprog plugin modified to fit new extension point description + added LanguageComponent [#38](https://github.com/eclipse/gemoc-studio-execution-ale/pull/38)
- [**enhancement**] validationRule added to languageComponent in plugin [#40](https://github.com/eclipse/gemoc-studio-execution-ale/pull/40)
- [**enhancement**] Added a console debug message indicating the implicit addons on start [#32](https://github.com/eclipse/gemoc-studio-execution-ale/pull/32)
- [**enhancement**] Change color of currentInstruction animation in example [#28](https://github.com/eclipse/gemoc-studio-execution-ale/pull/28)
- [**enhancement**] Clarifies Eclipse consoles used by the engines [#20](https://github.com/eclipse/gemoc-studio-execution-ale/pull/20)
- [**enhancement**] Use modified GEMOC standard icon in the launch conf for ALE [#9](https://github.com/eclipse/gemoc-studio-execution-ale/pull/9)
- [**enhancement**] Add concurrent engine to the studio [#8](https://github.com/eclipse/gemoc-studio-execution-ale/pull/8)
- [**enhancement**] Add command line eclipseapplication [#5](https://github.com/eclipse/gemoc-studio-execution-ale/pull/5)
- [**enhancement**] Integrate ALE interpreted engine in GEMOC Studio build [#1](https://github.com/eclipse/gemoc-studio-execution-ale/pull/1)

#### Bug Fixes:

- [**bug**] Bump to version of k3 including StepCommand return null fix [#59](https://github.com/eclipse/gemoc-studio-execution-ale/pull/59)
- [**bug**] Fix: remove self from step parameters [#58](https://github.com/eclipse/gemoc-studio-execution-ale/pull/58)
- [**bug**] Fix ALE Engine launcher error message handling [#41](https://github.com/eclipse/gemoc-studio-execution-ale/pull/41)
- [**bug**][**bump**] Use AleInterpreter close [#24](https://github.com/eclipse/gemoc-studio-execution-ale/pull/24)
- [**bug**][**bump**] Stop engine on error [#21](https://github.com/eclipse/gemoc-studio-execution-ale/pull/21)
- [**bug**] Fix: print error log for model executions [#18](https://github.com/eclipse/gemoc-studio-execution-ale/pull/18)
- [**bug**] Fix issue #13 [#16](https://github.com/eclipse/gemoc-studio-execution-ale/pull/16)
- [**bug**] Update references to ale.odesign in the aird of the example model [#4](https://github.com/eclipse/gemoc-studio-execution-ale/pull/4)

#### Refactorings

- [**refactoring**] Validator removed from plugin.xml [#42](https://github.com/eclipse/gemoc-studio-execution-ale/pull/42)
- [**refactoring**] Removes dependency to JavaEngine [#31](https://github.com/eclipse/gemoc-studio-execution-ale/pull/31)
- [**refactoring**] Use new GenericDebugModelId in order to decrease dependecies to JavaEngine [#30](https://github.com/eclipse/gemoc-studio-execution-ale/pull/30)

#### Version upgrades

- [**bump**] Bump to Eclipse 2022-06 [#55](https://github.com/eclipse/gemoc-studio-execution-ale/pull/55)
- [**bump**] Bump to 3.5.0 [#51](https://github.com/eclipse/gemoc-studio-execution-ale/pull/51)
- [**bump**] Bump eclipse 2021 12 [#52](https://github.com/eclipse/gemoc-studio-execution-ale/pull/52)
- [**releng**][**bump**] Bump Studio to 3.4.0 [#50](https://github.com/eclipse/gemoc-studio-execution-ale/pull/50)
- [**bump**] Bump to Eclipse 2021-06 [#49](https://github.com/eclipse/gemoc-studio-execution-ale/pull/49)
- [**bump**] Bump eclipse 2020-12 [#46](https://github.com/eclipse/gemoc-studio-execution-ale/pull/46)
- [**bump**] Bump to Eclipse 2020-03 [#43](https://github.com/eclipse/gemoc-studio-execution-ale/pull/43)
- [**bump**] Bump ALE version to 2019-06-24 [#19](https://github.com/eclipse/gemoc-studio-execution-ale/pull/19)

#### Release Engineering

- [**releng**] Use tpd for defining target platform [#53](https://github.com/eclipse/gemoc-studio-execution-ale/pull/53)
- [**releng**] Consolidation and automatic bump of K3 versions [#47](https://github.com/eclipse/gemoc-studio-execution-ale/pull/47)
- [**releng**] Explicit repository feature [#48](https://github.com/eclipse/gemoc-studio-execution-ale/pull/48)
- [**releng**] Deploy GEMOC artefacts to maven repository (repo.eclipse.org) [#33](https://github.com/eclipse/gemoc-studio-execution-ale/pull/33)
- [**releng**] Tycho 1.5 and p2 dependencies optimisation [#26](https://github.com/eclipse/gemoc-studio-execution-ale/pull/26)
- [**releng**] Update icons to official branding colors [#15](https://github.com/eclipse/gemoc-studio-execution-ale/pull/15)
- [**releng**] Fix xtend compilation issue 1373 [#2](https://github.com/eclipse/gemoc-studio-execution-ale/pull/2)

---

## v3.4.0 (10/01/2022)

#### Enhancements:

- [**enhancement**] Initial version of a Webprotocol based EngineAddon server [#54](https://github.com/eclipse/gemoc-studio-execution-ale/pull/54)
- [**bug**][**enhancement**] Improve management of ALE when  used as SiriusInterpreter [#45](https://github.com/eclipse/gemoc-studio-execution-ale/pull/45)
- [**enhancement**] Use general extension point [#25](https://github.com/eclipse/gemoc-studio-execution-ale/pull/25)
- [**enhancement**] Improve default Engine addon launch conf tab [#27](https://github.com/eclipse/gemoc-studio-execution-ale/pull/27)
- [**enhancement**] Validation plug-in for the Ale meta-programming approach in GEMOC Studio [#34](https://github.com/eclipse/gemoc-studio-execution-ale/pull/34)
- [**enhancement**] "metaprog" entry added to dsl files for the Ale example [#35](https://github.com/eclipse/gemoc-studio-execution-ale/pull/35)
- [**enhancement**] Metaprogramming approach name changed to FullyQualifiedName [#36](https://github.com/eclipse/gemoc-studio-execution-ale/pull/36)
- [**enhancement**] Example's metaprog entry fixed [#37](https://github.com/eclipse/gemoc-studio-execution-ale/pull/37)
- [**enhancement**] Metaprog plugin modified to fit new extension point description + added LanguageComponent [#38](https://github.com/eclipse/gemoc-studio-execution-ale/pull/38)
- [**enhancement**] validationRule added to languageComponent in plugin [#40](https://github.com/eclipse/gemoc-studio-execution-ale/pull/40)
- [**enhancement**] Added a console debug message indicating the implicit addons on start [#32](https://github.com/eclipse/gemoc-studio-execution-ale/pull/32)
- [**enhancement**] Change color of currentInstruction animation in example [#28](https://github.com/eclipse/gemoc-studio-execution-ale/pull/28)
- [**enhancement**] Clarifies Eclipse consoles used by the engines [#20](https://github.com/eclipse/gemoc-studio-execution-ale/pull/20)
- [**enhancement**] Use modified GEMOC standard icon in the launch conf for ALE [#9](https://github.com/eclipse/gemoc-studio-execution-ale/pull/9)
- [**enhancement**] Add concurrent engine to the studio [#8](https://github.com/eclipse/gemoc-studio-execution-ale/pull/8)
- [**enhancement**] Add command line eclipseapplication [#5](https://github.com/eclipse/gemoc-studio-execution-ale/pull/5)
- [**enhancement**] Integrate ALE interpreted engine in GEMOC Studio build [#1](https://github.com/eclipse/gemoc-studio-execution-ale/pull/1)

#### Bug Fixes:

- [**bug**] Fix ALE Engine launcher error message handling [#41](https://github.com/eclipse/gemoc-studio-execution-ale/pull/41)
- [**bug**][**bump**] Use AleInterpreter close [#24](https://github.com/eclipse/gemoc-studio-execution-ale/pull/24)
- [**bug**][**bump**] Stop engine on error [#21](https://github.com/eclipse/gemoc-studio-execution-ale/pull/21)
- [**bug**] Fix: print error log for model executions [#18](https://github.com/eclipse/gemoc-studio-execution-ale/pull/18)
- [**bug**] Fix issue #13 [#16](https://github.com/eclipse/gemoc-studio-execution-ale/pull/16)
- [**bug**] Update references to ale.odesign in the aird of the example model [#4](https://github.com/eclipse/gemoc-studio-execution-ale/pull/4)

#### Refactorings

- [**refactoring**] Validator removed from plugin.xml [#42](https://github.com/eclipse/gemoc-studio-execution-ale/pull/42)
- [**refactoring**] Removes dependency to JavaEngine [#31](https://github.com/eclipse/gemoc-studio-execution-ale/pull/31)
- [**refactoring**] Use new GenericDebugModelId in order to decrease dependecies to JavaEngine [#30](https://github.com/eclipse/gemoc-studio-execution-ale/pull/30)

#### Version upgrades

- [**bump**] Bump to 3.5.0 [#51](https://github.com/eclipse/gemoc-studio-execution-ale/pull/51)
- [**bump**] Bump eclipse 2021 12 [#52](https://github.com/eclipse/gemoc-studio-execution-ale/pull/52)
- [**releng**][**bump**] Bump Studio to 3.4.0 [#50](https://github.com/eclipse/gemoc-studio-execution-ale/pull/50)
- [**bump**] Bump to Eclipse 2021-06 [#49](https://github.com/eclipse/gemoc-studio-execution-ale/pull/49)
- [**bump**] Bump eclipse 2020-12 [#46](https://github.com/eclipse/gemoc-studio-execution-ale/pull/46)
- [**bump**] Bump to Eclipse 2020-03 [#43](https://github.com/eclipse/gemoc-studio-execution-ale/pull/43)
- [**bump**] Bump ALE version to 2019-06-24 [#19](https://github.com/eclipse/gemoc-studio-execution-ale/pull/19)

#### Release Engineering

- [**releng**] Use tpd for defining target platform [#53](https://github.com/eclipse/gemoc-studio-execution-ale/pull/53)
- [**releng**] Consolidation and automatic bump of K3 versions [#47](https://github.com/eclipse/gemoc-studio-execution-ale/pull/47)
- [**releng**] Explicit repository feature [#48](https://github.com/eclipse/gemoc-studio-execution-ale/pull/48)
- [**releng**] Deploy GEMOC artefacts to maven repository (repo.eclipse.org) [#33](https://github.com/eclipse/gemoc-studio-execution-ale/pull/33)
- [**releng**] Tycho 1.5 and p2 dependencies optimisation [#26](https://github.com/eclipse/gemoc-studio-execution-ale/pull/26)
- [**releng**] Update icons to official branding colors [#15](https://github.com/eclipse/gemoc-studio-execution-ale/pull/15)
- [**releng**] Fix xtend compilation issue 1373 [#2](https://github.com/eclipse/gemoc-studio-execution-ale/pull/2)

---

## v3.3.0 (28/07/2021)

#### Enhancements:

- [**bug**][**enhancement**] Improve management of ALE when  used as SiriusInterpreter [#45](https://github.com/eclipse/gemoc-studio-execution-ale/pull/45)

#### Version upgrades

- [**bump**] Bump to Eclipse 2021-06 [#49](https://github.com/eclipse/gemoc-studio-execution-ale/pull/49)
- [**bump**] Bump eclipse 2020-12 [#46](https://github.com/eclipse/gemoc-studio-execution-ale/pull/46)
- [**bump**] Bump to Eclipse 2020-03 [#43](https://github.com/eclipse/gemoc-studio-execution-ale/pull/43)

#### Release Engineering

- [**releng**] Consolidation and automatic bump of K3 versions [#47](https://github.com/eclipse/gemoc-studio-execution-ale/pull/47)
- [**releng**] Explicit repository feature [#48](https://github.com/eclipse/gemoc-studio-execution-ale/pull/48)

---

## v3.2.0 (16/06/2020)

#### Enhancements:

- [**enhancement**] Use general extension point [#25](https://github.com/eclipse/gemoc-studio-execution-ale/pull/25)
- [**enhancement**] Improve default Engine addon launch conf tab [#27](https://github.com/eclipse/gemoc-studio-execution-ale/pull/27)
- [**enhancement**] Validation plug-in for the Ale meta-programming approach in GEMOC Studio [#34](https://github.com/eclipse/gemoc-studio-execution-ale/pull/34)
- [**enhancement**] "metaprog" entry added to dsl files for the Ale example [#35](https://github.com/eclipse/gemoc-studio-execution-ale/pull/35)
- [**enhancement**] Metaprogramming approach name changed to FullyQualifiedName [#36](https://github.com/eclipse/gemoc-studio-execution-ale/pull/36)
- [**enhancement**] Example's metaprog entry fixed [#37](https://github.com/eclipse/gemoc-studio-execution-ale/pull/37)
- [**enhancement**] Metaprog plugin modified to fit new extension point description + added LanguageComponent [#38](https://github.com/eclipse/gemoc-studio-execution-ale/pull/38)
- [**enhancement**] validationRule added to languageComponent in plugin [#40](https://github.com/eclipse/gemoc-studio-execution-ale/pull/40)
- [**enhancement**] Added a console debug message indicating the implicit addons on start [#32](https://github.com/eclipse/gemoc-studio-execution-ale/pull/32)
- [**enhancement**] Change color of currentInstruction animation in example [#28](https://github.com/eclipse/gemoc-studio-execution-ale/pull/28)
- [**enhancement**] Clarifies Eclipse consoles used by the engines [#20](https://github.com/eclipse/gemoc-studio-execution-ale/pull/20)
- [**enhancement**] Use modified GEMOC standard icon in the launch conf for ALE [#9](https://github.com/eclipse/gemoc-studio-execution-ale/pull/9)
- [**enhancement**] Add concurrent engine to the studio [#8](https://github.com/eclipse/gemoc-studio-execution-ale/pull/8)
- [**enhancement**] Add command line eclipseapplication [#5](https://github.com/eclipse/gemoc-studio-execution-ale/pull/5)
- [**enhancement**] Integrate ALE interpreted engine in GEMOC Studio build [#1](https://github.com/eclipse/gemoc-studio-execution-ale/pull/1)

#### Bug Fixes:

- [**bug**] Fix ALE Engine launcher error message handling [#41](https://github.com/eclipse/gemoc-studio-execution-ale/pull/41)
- [**bug**][**bump**] Use AleInterpreter close [#24](https://github.com/eclipse/gemoc-studio-execution-ale/pull/24)
- [**bug**][**bump**] Stop engine on error [#21](https://github.com/eclipse/gemoc-studio-execution-ale/pull/21)
- [**bug**] Fix: print error log for model executions [#18](https://github.com/eclipse/gemoc-studio-execution-ale/pull/18)
- [**bug**] Fix issue #13 [#16](https://github.com/eclipse/gemoc-studio-execution-ale/pull/16)
- [**bug**] Update references to ale.odesign in the aird of the example model [#4](https://github.com/eclipse/gemoc-studio-execution-ale/pull/4)

#### Refactorings

- [**refactoring**] Validator removed from plugin.xml [#42](https://github.com/eclipse/gemoc-studio-execution-ale/pull/42)
- [**refactoring**] Removes dependency to JavaEngine [#31](https://github.com/eclipse/gemoc-studio-execution-ale/pull/31)
- [**refactoring**] Use new GenericDebugModelId in order to decrease dependecies to JavaEngine [#30](https://github.com/eclipse/gemoc-studio-execution-ale/pull/30)

#### Version upgrades

- [**bump**] Bump ALE version to 2019-06-24 [#19](https://github.com/eclipse/gemoc-studio-execution-ale/pull/19)

#### Release Engineering

- [**releng**] Deploy GEMOC artefacts to maven repository (repo.eclipse.org) [#33](https://github.com/eclipse/gemoc-studio-execution-ale/pull/33)
- [**releng**] Tycho 1.5 and p2 dependencies optimisation [#26](https://github.com/eclipse/gemoc-studio-execution-ale/pull/26)
- [**releng**] Update icons to official branding colors [#15](https://github.com/eclipse/gemoc-studio-execution-ale/pull/15)
- [**releng**] Fix xtend compilation issue 1373 [#2](https://github.com/eclipse/gemoc-studio-execution-ale/pull/2)

---

## v3.2.0-20191216 (16/12/2019)

#### Enhancements:

- [**enhancement**] Clarifies Eclipse consoles used by the engines [#20](https://github.com/eclipse/gemoc-studio-execution-ale/pull/20)

#### Bug Fixes:

- [**bug**][**bump**] Use AleInterpreter close [#24](https://github.com/eclipse/gemoc-studio-execution-ale/pull/24)
- [**bug**][**bump**] Stop engine on error [#21](https://github.com/eclipse/gemoc-studio-execution-ale/pull/21)

#### Release Engineering

- [**releng**] Tycho 1.5 and p2 dependencies optimisation [#26](https://github.com/eclipse/gemoc-studio-execution-ale/pull/26)

---

## v3.1.0 (29/07/2019)
*No changelog for this release.*

---

## v3.1.0-20190627 (27/06/2019)

#### Enhancements:

- [**enhancement**] Use modified GEMOC standard icon in the launch conf for ALE [#9](https://github.com/eclipse/gemoc-studio-execution-ale/pull/9)
- [**enhancement**] Add concurrent engine to the studio [#8](https://github.com/eclipse/gemoc-studio-execution-ale/pull/8)
- [**enhancement**] Add command line eclipseapplication [#5](https://github.com/eclipse/gemoc-studio-execution-ale/pull/5)
- [**enhancement**] Integrate ALE interpreted engine in GEMOC Studio build [#1](https://github.com/eclipse/gemoc-studio-execution-ale/pull/1)

#### Bug Fixes:

- [**bug**] Fix: print error log for model executions [#18](https://github.com/eclipse/gemoc-studio-execution-ale/pull/18)
- [**bug**] Fix issue #13 [#16](https://github.com/eclipse/gemoc-studio-execution-ale/pull/16)
- [**bug**] Update references to ale.odesign in the aird of the example model [#4](https://github.com/eclipse/gemoc-studio-execution-ale/pull/4)

#### Version upgrades

- [**bump**] Bump ALE version to 2019-06-24 [#19](https://github.com/eclipse/gemoc-studio-execution-ale/pull/19)

#### Release Engineering

- [**releng**] Update icons to official branding colors [#15](https://github.com/eclipse/gemoc-studio-execution-ale/pull/15)
- [**releng**] Fix xtend compilation issue 1373 [#2](https://github.com/eclipse/gemoc-studio-execution-ale/pull/2)
