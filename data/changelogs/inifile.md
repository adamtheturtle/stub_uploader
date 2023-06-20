## 0.4.0.1 (2023-06-08)

inifile: add missing attributes (#10273)

And make many attributes read-only. The primary entry point to this module in `IniFile` (or its subclass
`AppIniFile`). Since the config file is read (from `filename`) and
parsed (using the `dialect`) in the `IniFile` constructor, modifying
attributes like `IniFile.filename` or `IniFile.dialect` after
construction is likely to cause problems.

## 0.4.0.0 (2023-06-07)

Add stubs for `inifile` (#10270)
