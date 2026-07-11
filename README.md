# CGU-SIM Briefing Package

This project root is intentionally kept small.

## Final Deliverables

Use `CGU_SIM_Briefing_Package/` for distribution:

- `CGU_SIM_Briefing_EN.pptx`
- `CGU_SIM_合作簡報_繁體中文.pptx`
- `CGU_SIM_Briefing_Report_OnePage.html`
- `CGU_SIM_Briefing_EN.docx`
- `CGU_SIM_合作簡報_繁體中文.docx`

The slide decks, one-page HTML report, and Word reports are maintained as equivalent briefing content in different formats. Substantive future edits should be synchronized across all formats and reflected in `Prompt.md`.

The slide decks, HTML report, and Word reports include a clickable link/button to the public chatbot.

## Public Chatbot

Use `CGU_SIM_Chatbot_Site/` for the public shareable CGU-SIM collaboration assistant.

- Local review file: `CGU_SIM_Chatbot_Site/index.html`
- Public deployment: https://cgu-sim-chatbot.cguaacsb.chatgpt.site
- The chatbot is maintained as another equivalent public-facing format of the briefing package. Substantive future edits should update its knowledge base together with the slide decks, HTML report, Word reports, and `Prompt.md`.
- The chatbot must not reveal internal source filenames, media filenames, recording practices, or private evidence-handling notes.

## Internal Archive

`_Internal_Archive_20260711/` preserves materials that are not meant for public distribution:

- `source_materials/`: original source documents and internal conversation materials.
- `generated_working_files/`: React source workspace, deck/report build scripts, and older presentation references.
- `system_metadata/`: local metadata moved out of the project root.

The archive is retained so the briefing can be regenerated or audited later without cluttering the root folder.
