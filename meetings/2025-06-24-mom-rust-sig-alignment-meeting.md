# Rust SiG Meeting on 2025-06-24

## Agenda

1. Acceptance of Previous Meeting Minutes
2. Explore another notetaking tool

   1. GitHub (discussions) example Eclipse S-CORE
      [https://github.com/orgs/eclipse-score/discussions/categories/architecture-community](https://github.com/orgs/eclipse-score/discussions/categories/architecture-community)
   2. GitLabs example Automotive Process SIG
      [https://gitlab.eclipse.org/eclipse-wg/sdv-wg/sdv-sig-automotivegradeos/meetings/-/blob/main/MeetingNotes.md?ref_type=heads](https://gitlab.eclipse.org/eclipse-wg/sdv-wg/sdv-sig-automotivegradeos/meetings/-/blob/main/MeetingNotes.md?ref_type=heads)
   3. Mailing-lists
   4. Suggestion for decision ([florian.gilcher@ferrous-systems.com](mailto:florian.gilcher@ferrous-systems.com) needed)
   5. T: Markus will drop a mail to Florian
3. Publishing the "Eclipse Rust SIG” Oxidize Conference KeyNote
   1. Share other projects that are written in Rust
   2. Eclipse uProtocol
   3. iceoryx2
   4. Eclipse Zenoh
   5. Eclipse Kuksa
   6. Eclipse Ankaios
   7. Eclipse S-Core e.g. [https://github.com/eclipse-score/inc_feo/](https://github.com/eclipse-score/inc_feo/)
   8. Eclipse openSOVD (under public review) [https://projects.eclipse.org/proposals/eclipse-opensovd](https://projects.eclipse.org/proposals/eclipse-opensovd)
4. Rust API for S-CORE mw_com
    1. Discussion about API design
        1. On top of C++ (still safe?) or totally bad?
        2. Look inside uProtocol API design may help
        3. uProtocol API is bound to[protobuf-spec](https://github.com/eclipse-uprotocol/up-rust) (protobuf compiler)
        4. Not ideal as the protobuf compiler is not optimal for Rust (learning)
        5. In contact with Autosar Safety WG (Subgroup Rust, Christoph Petig). Idea is to use WASI
        6. Most important is to be independent from different programming languages
5. Communication around the SDV WG:
    1. [https://www.vda.de/en/press/press-releases/2025/250624_PM_Automotive_industry_signs_Memorandum_of_Understanding](https://www.vda.de/en/press/press-releases/2025/250624_PM_Automotive_industry_signs_Memorandum_of_Understanding)
6. Next meeting Notes: Daniel Krippner

Supplemental material to the agenda can be found in [Material](https://docs.google.com/document/d/1Ne7jPoQFIw2B5isovub7pSf2zRH7-vLlOOt3sOnyj1s/edit#heading=h.1n00rlbbbdjj)

## Check-in area

Please add your name, and an emoji that describes your day.

* Heissenberger, Christian 😢
* Hosch, Markus 🙌👌
* Elena Gantner😶‍🌫️
* Priyaa
* Daniel Krippner 😅

Notetaker:
Christian Heissenberger
