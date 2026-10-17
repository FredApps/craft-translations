# Craft translations: Spanish pilot

This data-only repository contains 11 proposed shared Spanish UI actions for the CraftLingo pilot, with app-specific overrides supported by the schema. It contains no executable tooling, trusted approvals or application source.

The trusted validator, semantic bindings, provenance links and approval policy live in [CraftLingo](https://github.com/FredApps/craftlingo). The initial policy has zero approvals, so these proposals do not change any application translation. Existing WordCraft and PdfCraft catalogs remain untouched.

## Contributing

Propose corrections through a pull request to `catalogs/es/common.json`. Include the app/screen context and explain regional or semantic differences. Do not add an `approved` flag: catalog content cannot approve itself. Maintainers must review the exact text and binding separately in the trusted tooling repository.

Pilot actions: Save, Undo, Redo, Copy, Cut, Cancel, Close, Apply, Print, OK and Browse…. Identical English labels are not enough to establish shared meaning. Open and Select All are deliberately excluded from this pilot because the observed usage differs.

Imported or AI-authored text remains a candidate until a reviewer approves it. Native Spanish review is still needed. Do not submit private documents, credentials or personal information as translation context.

## Limits

No editor service is connected. No app integration, plural migration or release is claimed. Only ordinary text is supported in the initial validator; reserved plural/ID contexts are rejected. Regional style remains app-owned.
