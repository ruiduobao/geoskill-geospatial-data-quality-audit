# geoskill-geospatial-data-quality-audit

> Unified geospatial data quality audit for GIS data packages. Checks raster, vector, table, NetCDF, and directory structure. Outputs JSON/HTML reports, issue layers, checksums, and machine-readable exit codes. Use when the user wants to validate data packages, check delivery quality, find CRS/nodata/ geometry issues, or generate QA reports.

See [SKILL.md](SKILL.md) for full usage, inputs and outputs.

## Quick start

```bash
python geospatial_data_quality_audit.py /path/to/your/data --html --issues-geojson
```

## License

MIT
