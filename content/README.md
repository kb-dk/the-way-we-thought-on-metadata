# Content

## Title

* Titel, Title
* Transcribed title
* Alternative title
* Subtitle

```
  <md:titleInfo xml:lang="he">
     <md:title>סדר הגדה של פסח</md:title>
  </md:titleInfo>
  <md:titleInfo xml:lang="en">
     <md:title>Seder hagada shel Pesaḥ</md:title>
  </md:titleInfo>
```

## Subject

### Geographic Subjects

```  
   <md:subject xml:lang="da">
      <md:hierarchicalGeographic>
        <md:area areaType="area" displayLabel="lokalitet">Kallerup</md:area>
        <md:area areaType="cadastre" displayLabel="matrikelnummer">Kallerup By</md:area>
        <md:area areaType="parish" displayLabel="sogn">Kallerup</md:area>
        <md:citySection citySectionType="zipcode" displayLabel="postnummer">7700</md:citySection>
        <md:citySection citySectionType="housenumber" displayLabel="husnummer">8</md:citySection>
        <md:citySection citySectionType="street" displayLabel="vejnavn">Kallerupvadested</md:citySection>
        <md:city>Thisted</md:city>
      </md:hierarchicalGeographic>
    </md:subject>
```

### Coordinates

```
   <md:subject>
      <md:cartographics>
        <md:coordinates>56.913092436935194,8.57781772576134</md:coordinates>
      </md:cartographics>
    </md:subject>
```


* Motiv
* Person
* Lokalitet
* Georeference (Scale)
* Bygningsnavn
* Category, Subject, Keywords
* LCSH

## Description
## Type

The type vocabulary used is a bit involved. First, resource type (and collection) is implied in the URIs

* /editions - The collection of editions 

* /pamphlets - The ephemeras are here
* /manus - The manuscripts, rare books and archival records except letters
* /images - Still images
* /letters - Letters and post cards
* /maps - Maps
* /books - Rare books 

The digitized are in general not in these services (they are disseminated through the library's OPAC). To a large extent the type of a resource is derived from its URI.

| Type | Value source | COP/Mods | Definition |
|:-----|:-------------|:---------|:-----------|
| Manuscript | | |["A resource that is written in handwriting or typescript"](https://www.loc.gov/standards/mods/userguide/typeofresource.html#manuscript) |
| Collection | [DCMI Type: Collection](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/dcmitype/Collection) | &lt;typeOfResource collection="yes">still image&lt;/typeOfResource> | ["A made-up multipart group of items that were not originally published, distributed, or produced together"](https://www.loc.gov/standards/mods/userguide/typeofresource.html#collection) |
| DataSet | [DCMI Type: Dataset](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/dcmitype/Dataset) | software AND database |
| Service | [DCMI Type: Dataset](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/dcmitype/Service) | software AND online system or service |
| Software | [DCMI Type: Dataset](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/dcmitype/Software)  | software |
| Image | | cartographic material |
| InteractiveResource | | multimedia |
| MovingImage | | moving image |
| PhysicalObject | | three-dimensional object |
| Sound | | sound recording |
| Image | | still image |
| Text | | text
| Text | | notated music |
| map | | Kort |

## Source
## Relation



```
  <md:relatedItem displayLabel="Publication" type="host">
     <md:titleInfo xml:lang="da">
        <md:title>B.T.</md:title>
     </md:titleInfo>
  </md:relatedItem>
```
http://www5.kb.dk/images/billed/2010/okt/billeder/object356751/da/

```
  <md:relatedItem type="event">
      <md:note xml:lang="da">Revykomedie af Abell, Kjeld (1901-1961) dramatiker</md:note>
      <md:originInfo>
          <md:dateIssued xml:lang="da">1987</md:dateIssued>
          <md:place>
             <md:placeTerm xml:lang="da">Hvidovre Teater, Hvidovre</md:placeTerm>
          </md:place>
      </md:originInfo>
  </md:relatedItem>
```
http://www5.kb.dk/images/billed/2010/okt/billeder/object356751/da/

## Coverage

