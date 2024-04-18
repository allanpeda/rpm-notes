# These are notes regarding the use of RPM `.spec` files gleaned after many years.

1. Typical binaries can be build with only a source archive and a controlling `*.spec` file.
1. The `*.spec` is useful as a basis for developing a Software Bill of Materials (SBOM).
1. With some effort, spec files can validate checksums and developer PGP signatures.
1. There are many built in macros which may be relied on, such as `%__make` and `%__awk`.
