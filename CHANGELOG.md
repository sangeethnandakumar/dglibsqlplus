# Changelog

- Major stable version
- Tested on DataGrip 2025.3.5.1
- Fixed SQL dialect bug that causing libSql errors when editing cells and commiting directly from DataGrip table viewer. This was happening because DataGrip autogenerates UPDATE queries that isn't SQLite compatable due to dilect variation