# Manufacturing outputs

- [Gerbers/](Gerbers/): outputs extracted from the unchanged original GitHub project ZIP; associated with the earlier supplied archive.
- [Local_Revision_2026-10-06/Gerbers/](Local_Revision_2026-10-06/Gerbers/): later local files recovered on 2026-10-06, with copper, masks, front silkscreen, board outline, Gerber job file and plated/non-plated drill files.
- [Local source snapshot](../Documentation/Local_Revision_2026-10-06/KiCad_Project/): retained for traceability because local PCB geometry differs from the primary GitHub revision. The snapshot retains the original local plot path `Gerbers/`; choose an explicit output folder when regenerating.
- [BOM](../BOM/555_Timer_LED_Blinker.csv): recovered local BOM export.

These files are supplied outputs, not a newly regenerated or independently approved fabrication package. The 2026-10-05 ERC/DRC snapshots apply to the older GitHub revision. Rerun checks and regenerate a consistent set from the selected source before fabrication. No separate final Gerber ZIP or manufacturing instruction document was found in the local project folder.
