## Membuat file Json dan XML

```json
[
	{
		"Name": "Debian",
		"Version": "9",
		"Install": "apt",
		"Owner": "SPI",
		"Kernel": "4.9"
	},
	{
		"Name": "Ubuntu",
		"Version": "17.10",
		"Install": "apt",
		"Owner": "Canonical",
		"Kernel": "4.13"
	},
	{
		"Name": "Fedora",
		"Version": "26",
		"Install": "dnf",
		"Owner": "Red Hat",
		"Kernel": "4.13"
	},
	{
		"Name": "CentOS",
		"Version": "7",
		"Install": "yum",
		"Owner": "Red Hat",
		"Kernel": "3.10"
	},
	{
		"Name": "OpenSUSE",
		"Version": "42.3",
		"Install": "zypper",
		"Owner": "Novell",
		"Kernel": "4.4"
	},
	{
		"Name": "Arch Linux",
		"Version": "Rolling Release",
		"Install": "pacman",
		"Owner": "SPI",
		"Kernel": "4.13"
	},
	{
		"Name": "Gentoo",
		"Version": "Rolling Release",
		"Install": "emerge",
		"Owner": "Gentoo Foundation",
		"Kernel": "4.12"
	}
]
```
## Membuat File XML (Extensible Markup Language)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<root>
   <element>
      <Install>apt</Install>
      <Kernel>4.9</Kernel>
      <Name>Debian</Name>
      <Owner>SPI</Owner>
      <Version>9</Version>
   </element>
   <element>
      <Install>apt</Install>
      <Kernel>4.13</Kernel>
      <Name>Ubuntu</Name>
      <Owner>Canonical</Owner>
      <Version>17.10</Version>
   </element>
   <element>
      <Install>dnf</Install>
      <Kernel>4.13</Kernel>
      <Name>Fedora</Name>
      <Owner>Red Hat</Owner>
      <Version>26</Version>
   </element>
   <element>
      <Install>yum</Install>
      <Kernel>3.10</Kernel>
      <Name>CentOS</Name>
      <Owner>Red Hat</Owner>
      <Version>7</Version>
   </element>
   <element>
      <Install>zypper</Install>
      <Kernel>4.4</Kernel>
      <Name>OpenSUSE</Name>
      <Owner>Novell</Owner>
      <Version>42.3</Version>
   </element>
   <element>
      <Install>pacman</Install>
      <Kernel>4.13</Kernel>
      <Name>Arch Linux</Name>
      <Owner>SPI</Owner>
      <Version>Rolling Release</Version>
   </element>
   <element>
      <Install>emerge</Install>
      <Kernel>4.12</Kernel>
      <Name>Gentoo</Name>
      <Owner>Gentoo Foundation</Owner>
      <Version>Rolling Release</Version>
   </element>
</root>
```
kita beri nama kedua file tersebut dengan
os.json
os.xml
