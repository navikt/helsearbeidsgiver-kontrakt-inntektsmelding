# helsearbeidsgiver-kontrakt-inntektsmelding
XSD og kodegenerering fra foreldrepenger-prosjektet:

(https://github.com/navikt/fp-kontrakter/blob/master/vl-kontrakt-inntektsmelding) - commit a616dcb

med diverse forbedringer
* global.xjb : generateElementProperty="false" gjør at genererte elementer ikke wrappes med JAXBEelement
* jaxb-xew-plugin lar oss slippe lister av lister (https://github.com/dmak/jaxb-xew-plugin)

HOWTO:

```mvn clean install```