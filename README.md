# Building the fonts

Fonts are built using the gftools builder, which is a python based font builder.

To install the dependencies and build the fonts, do the following in this directory:

```
python3 -m venv venv
gftools builder sources/config-texte.yaml
gftools builder sources/config-titre.yaml
```

You should now have a `/fonts` directory containing different font binaries for both families.