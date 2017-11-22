# materialize-grid-system 
----
A simple implementation of Materializecss Grid System using Polymer Elements

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/aaroncadillac/materialize-grid-system)

## Install 

    bower i --save materialize-grid-system

## Usage 

Contains cols into a row for a correct functionallity

    <mgs-row>
       <mgs-col> Column contain</mgs-col>
    </mgs-row>

## Properties

The Materialize Grid System is based on a 12-column grid and uses 4 screen measures to manage the responsive behavior

- S (Small) Phones recomended
- M (Medium) Tblets recomended
- L (Large) Small size PC recomended
- XL (Extra Large) Large size PC recomended

### Using with properties

    <mgs-row>
      <mgs-col s="12" m="3">col s12 m3</mgs-col>
      <mgs-col s="12" m="3" l="4">col s12 m3 l4</mgs-col>
      <mgs-col s="12" m="3" l="4" xl="6">col s12 m3</mgs-col>
    </mgs-row>


