# Campeche: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Campeche, Mexico, which global-law reads at `mexico/campeche/acts/`.

The law of the State of Campeche (Estado Libre y Soberano de Campeche, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-cam/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

143 ordenamientos with 1053 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE CAMPECHE -ANTES CONSTITUCION POLITICO-SOCIAL DEL ESTADO DE CAMPECHE- | 133 | as first published, then each reform: 8 July 1917 to 5 September 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE CAMPECHE | 63 | oldest version available, then each reform: 19 May 1944 to 23 July 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES | 25 | as first published, then each reform: 27 December 1942 to 1 January 2018 |
| `codigo-de-procedimientos-contencioso-administrativos/` | CODIGO DE PROCEDIMIENTOS CONTENCIOSO- ADMINISTRATIVOS DEL ESTADO DE CAMPECHE | 6 | as first published, then each reform: 4 January 1997 to 29 August 2017 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE CAMPECHE | 15 | as first published, then each reform: 11 December 2008 to 30 December 2025 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 27 December 2013 to 1 January 2020 |
| `codigo-penal/` | CODIGO PENAL DEL ESTADO DE CAMPECHE | 82 | as first published, then each reform: 23 July 2012 to 30 July 2026 |
| `ley-agricola/` | LEY AGRICOLA DEL ESTADO DE CAMPECHE | 5 | as first published, then each reform: 11 July 2000 to 8 April 2026 |
| `ley-constitutiva-de-la-fundacion-pablo-garcia/` | LEY CONSTITUTIVA DE LA FUNDACION PABLO GARCIA DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 18 November 2013 to 8 December 2016 |
| `ley-constitutiva-de-la-universidad-autonoma-del-carmen-antes/` | LEY CONSTITUTIVA DE LA UNIVERSIDAD AUTONOMA DEL CARMEN -ANTES LEY CONSTITUTIVA DE LA UNIVERSIDAD DEL CARMEN- | 3 | as first published, then each reform: 14 June 1967 to 18 November 2012 |
| `ley-constitutiva-del-instituto-campechano/` | LEY CONSTITUTIVA DEL INSTITUTO CAMPECHANO | 1 | as first published: 2 February 2010 |
| `ley-constitutiva-del-premio-al-merito-de-la-enfermeria-campe/` | LEY CONSTITUTIVA DEL PREMIO AL MERITO DE LA ENFERMERIA CAMPECHANA | 3 | as first published, then each reform: 4 May 2002 to 8 April 2026 |
| `ley-constitutiva-del-reconocimiento-a-la-gestion-gubernament/` | LEY CONSTITUTIVA DEL RECONOCIMIENTO A LA GESTION GUBERNAMENTAL | 1 | as first published: 1 August 2003 |
| `ley-constitutiva-del-reconocimiento-al-maestro-emerito-campe/` | LEY CONSTITUTIVA DEL RECONOCIMIENTO AL "MAESTRO EMERITO CAMPECHANO" | 1 | as first published: 29 December 2013 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA DEL ESTADO DE CAMPECHE | 24 | as first published, then each reform: 7 July 2007 to 9 June 2026 |
| `ley-de-adquisiciones-arrendamientos-y-prestacion-de-servicio/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y PRESTACION DE SERVICIOS RELACIONADOS CON BIENES MUEBLES DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 13 January 1991 to 1 July 2001 |
| `ley-de-agua-potable-y-alcantarillado/` | LEY DE AGUA POTABLE Y ALCANTARILLADO DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 22 December 1992 to 20 June 2017 |
| `ley-de-amnistia/` | LEY DE AMNISTIA DEL ESTADO DE CAMPECHE | 1 | as first published: 28 July 2023 |
| `ley-de-apicultura/` | LEY DE APICULTURA DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 20 July 2008 to 30 November 2013 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE CAMPECHE | 1 | as first published: 7 May 2010 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO PARA EL ESTADO DE CAMPECHE | 1 | as first published: 26 July 2025 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 7 April 2000 to 13 September 2013 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO-PRIVADAS DEL ESTADO DE CAMPECHE | 1 | as first published: 27 December 2023 |
| `ley-de-austeridad-y-ahorro/` | LEY DE AUSTERIDAD Y AHORRO DEL ESTADO DE CAMPECHE Y SUS MUNICIPIOS | 4 | as first published, then each reform: 30 December 2023 to 23 March 2026 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE CAMPECHE Y DE SUS MUNICIPIOS | 2 | as first published, then each reform: 4 June 2008 to 16 February 2023 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE CAMPECHE | 1 | as first published: 11 November 2020 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE CAMPECHE | 5 | as first published, then each reform: 12 April 1992 to 12 May 2023 |
| `ley-de-cooperacion-de-los-particulares-para-obras-publicas-e/` | LEY DE COOPERACION DE LOS PARTICULARES PARA OBRAS PUBLICAS EN EL ESTADO | 1 | as first published: 17 May 1944 |
| `ley-de-coordinacion-en-materia-de-zonas-economicas-especiale/` | LEY DE COORDINACION EN MATERIA DE ZONAS ECONOMICAS ESPECIALES Y AREAS DE INFLUENCIA DEL ESTADO DE CAMPECHE | 1 | as first published: 25 February 2017 |
| `ley-de-defensoria-publica-y-asistencia-juridica-gratuita/` | LEY DE DEFENSORIA PUBLICA Y ASISTENCIA JURIDICA GRATUITA DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 3 December 2014 to 21 March 2026 |
| `ley-de-derechos-cultura-y-organizacion-de-los-pueblos-y-comu/` | LEY DE DERECHOS, CULTURA Y ORGANIZACION DE LOS PUEBLOS Y COMUNIDADES INDIGENAS DEL ESTADO DE CAMPECHE | 6 | as first published, then each reform: 30 June 2000 to 15 March 2019 |
| `ley-de-desarrollo-cultural/` | LEY DE DESARROLLO CULTURAL DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 12 November 2013 to 10 November 2022 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE CAMPECHE | 5 | as first published, then each reform: 1 January 2009 to 9 April 2020 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE CAMPECHE | 8 | as first published, then each reform: 1 January 2008 to 18 May 2026 |
| `ley-de-disciplina-financiera-y-responsabilidad-hacendaria/` | LEY DE DISCIPLINA FINANCIERA Y RESPONSABILIDAD HACENDARIA DEL ESTADO DE CAMPECHE Y SUS MUNICIPIOS | 5 | as first published, then each reform: 19 November 2016 to 30 December 2025 |
| `ley-de-educacion-ambiental/` | LEY DE EDUCACION AMBIENTAL DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 1 January 2009 to 10 December 2022 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE CAMPECHE | 37 | as first published, then each reform: 2 June 1993 to 2 October 2026 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA-RECEPCION DEL ESTADO DE CAMPECHE Y SUS MUNICIPIOS | 1 | as first published: 3 March 2021 |
| `ley-de-expropiacion-y-demas-limitaciones-al-derecho-de-propi/` | LEY DE EXPROPIACION Y DEMAS LIMITACIONES AL DERECHO DE PROPIEDAD DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 16 January 1981 to 6 September 2025 |
| `ley-de-firma-electronica-avanzada-y-uso-de-medios-electronic/` | LEY DE FIRMA ELECTRONICA AVANZADA Y USO DE MEDIOS ELECTRONICOS DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 3 December 2014 to 1 April 2017 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 19 July 2017 to 10 November 2021 |
| `ley-de-fomento-a-la-investigacion-cientifica-y-tecnologica/` | LEY DE FOMENTO A LA INVESTIGACION CIENTIFICA Y TECNOLOGICA DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 3 September 2006 to 7 August 2021 |
| `ley-de-fomento-a-la-produccion-de-alimentos-basicos/` | LEY DE FOMENTO A LA PRODUCCION DE ALIMENTOS BASICOS DEL ESTADO DE CAMPECHE | 1 | as first published: 4 April 1981 |
| `ley-de-fomento-de-la-lectura-y-del-libro/` | LEY DE FOMENTO DE LA LECTURA Y DEL LIBRO DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 19 January 2014 to 10 March 2023 |
| `ley-de-fomento-pecuario/` | LEY DE FOMENTO PECUARIO PARA EL ESTADO DE CAMPECHE | 3 | oldest version available, then each reform: 1 January 2016 to 1 January 2021 |
| `ley-de-fraccionamientos-unidades-habitacionales-condominios/` | LEY DE FRACCIONAMIENTOS, UNIDADES HABITACIONALES, CONDOMINIOS Y USO DE INMUEBLES EN TIEMPO COMPARTIDO DEL ESTADO DE CAMPECHE | 1 | as first published: 16 May 1980 |
| `ley-de-hacienda-de-los-municipios/` | LEY DE HACIENDA DE LOS MUNICIPIOS DEL ESTADO DE CAMPECHE | 31 | as first published, then each reform: 5 December 1993 to 1 May 2022 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE CAMPECHE | 27 | as first published, then each reform: 24 December 2009 to 1 January 2026 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE CAMPECHE PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-calakmul-campeche-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE CALAKMUL, CAMPECHE, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-escarcega-campeche-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE ESCARCEGA, CAMPECHE, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-de-asistencia-privada/` | LEY DE INSTITUCIONES DE ASISTENCIA PRIVADA DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 17 August 1996 to 11 April 2000 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES DEL ESTADO DE CAMPECHE | 12 | as first published, then each reform: 1 July 2014 to 29 August 2026 |
| `ley-de-justicia-civica/` | LEY DE JUSTICIA CIVICA PARA EL ESTADO DE CAMPECHE | 1 | as first published: 30 December 2023 |
| `ley-de-la-administracion-publica-paraestatal/` | LEY DE LA ADMINISTRACION PUBLICA PARAESTATAL DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 23 July 2010 to 30 December 2025 |
| `ley-de-la-comision-de-conciliacion-y-arbitraje-medico-antes/` | LEY DE LA COMISION DE CONCILIACION Y ARBITRAJE MEDICO -- ANTES LEY DE LA COMISION DE ARBITRAJE MEDICO -- DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 1 January 2010 to 16 October 2016 |
| `ley-de-la-comision-de-derechos-humanos/` | LEY DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE CAMPECHE | 7 | as first published, then each reform: 2 January 1993 to 17 May 2024 |
| `ley-de-la-escuela-normal-de-profesores-de-calkini/` | LEY DE LA ESCUELA NORMAL DE PROFESORES DE CALKINI | 1 | as first published: 16 July 1967 |
| `ley-de-la-infraestructura-fisica-educativa/` | LEY DE LA INFRAESTRUCTURA FISICA EDUCATIVA DEL ESTADO DE CAMPECHE | 1 | as first published: 20 December 2008 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD DEL ESTADO DE CAMPECHE | 9 | as first published, then each reform: 12 August 2011 to 10 June 2026 |
| `ley-de-la-universidad-autonoma-de-campeche-antes-ley-constit/` | LEY DE LA UNIVERSIDAD AUTONOMA DE CAMPECHE -ANTES LEY CONSTITUTIVA DE LA UNIVERSIDAD DEL SUDESTE- | 2 | as first published, then each reform: 1 September 1965 to 20 October 1989 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE CAMPECHE | 27 | as first published, then each reform: 3 June 2015 to 14 October 2026 |
| `ley-de-los-trabajadores-al-servicio-de-los-poderes-municipio/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES, MUNICIPIOS E INSTITUCIONES DESCENTRALIZADAS DEL ESTADO DE CAMPECHE | 10 | as first published, then each reform: 12 September 1979 to 9 August 2025 |
| `ley-de-los-trabajadores-al-servicio-del-gobierno/` | LEY DE LOS TRABAJADORES AL SERVICIO DEL GOBIERNO DEL ESTADO DE CAMPECHE | 11 | as first published, then each reform: 23 June 1996 to 9 August 2025 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL DEL ESTADO DE CAMPECHE | 9 | as first published, then each reform: 29 July 2023 to 19 June 2026 |
| `ley-de-obligaciones-financiamientos-y-deuda-publica/` | LEY DE OBLIGACIONES, FINANCIAMIENTOS Y DEUDA PUBLICA DEL ESTADO DE CAMPECHE Y SUS MUNICIPIOS | 2 | as first published, then each reform: 5 November 2016 to 23 December 2023 |
| `ley-de-obras-publicas/` | LEY DE OBRAS PUBLICAS DEL ESTADO DE CAMPECHE | 11 | as first published, then each reform: 1 September 1984 to 13 July 2024 |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES DEL ESTADO DE CAMPECHE | 7 | as first published, then each reform: 5 March 2009 to 13 March 2026 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE CAMPECHE Y SUS MUNICIPIOS | 1 | as first published: 17 October 2018 |
| `ley-de-prevencion-y-atencion-de-la-violencia-intrafamiliar/` | LEY DE PREVENCION Y ATENCION DE LA VIOLENCIA INTRAFAMILIAR PARA EL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 27 July 2002 to 22 August 2015 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO PARA EL ESTADO Y LOS MUNICIPIOS DE CAMPECHE | 1 | as first published: 20 March 2008 |
| `ley-de-procedimientos-para-la-eleccion-de-comisarios-municip/` | LEY DE PROCEDIMIENTOS PARA LA ELECCION DE COMISARIOS MUNICIPALES DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 4 April 2008 to 29 June 2017 |
| `ley-de-proteccion-a-la-salud-de-los-no-fumadores-en-el-estad/` | LEY DE PROTECCION A LA SALUD DE LOS NO FUMADORES EN EL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 17 July 2009 to 11 July 2018 |
| `ley-de-proteccion-civil-prevencion-y-atencion-de-desastres/` | LEY DE PROTECCION CIVIL, PREVENCION Y ATENCION DE DESASTRES DEL ESTADO DE CAMPECHE | 5 | as first published, then each reform: 19 November 2011 to 10 October 2024 |
| `ley-de-proteccion-de-adultos-mayores/` | LEY DE PROTECCION DE ADULTOS MAYORES PARA EL ESTADO DE CAMPECHE | 13 | oldest version available, then each reform: 28 July 2005 to 18 June 2026 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 27 July 2017 to 11 June 2026 |
| `ley-de-proteccion-conservacion-y-fomento-de-arbolado-y-areas/` | LEY DE PROTECCION, CONSERVACION Y FOMENTO DE ARBOLADO Y AREAS VERDES URBANAS DEL ESTADO DE CAMPECHE | 1 | as first published: 29 April 2022 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE CAMPECHE Y SUS MUNICIPIOS | 1 | as first published: 1 January 2024 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL PARA EL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 19 October 2018 to 28 June 2024 |
| `ley-de-salud/` | LEY DE SALUD PARA EL ESTADO DE CAMPECHE | 44 | as first published, then each reform: 14 May 2008 to 2 October 2026 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR PARA EL ESTADO DE CAMPECHE | 1 | as first published: 25 September 2014 |
| `ley-de-seguridad-publica/` | LEY DE SEGURIDAD PUBLICA DEL ESTADO DE CAMPECHE | 7 | as first published, then each reform: 4 December 2014 to 10 October 2024 |
| `ley-de-seguridad-y-servicios-sociales-de-los-trabajadores/` | LEY DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DEL ESTADO DE CAMPECHE | 12 | as first published, then each reform: 4 June 1987 to 24 September 2019 |
| `ley-de-servicios-periciales/` | LEY DE SERVICIOS PERICIALES DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 3 December 2014 to 9 May 2015 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE CAMPECHE | 8 | as first published, then each reform: 5 May 2016 to 11 June 2026 |
| `ley-de-transporte/` | LEY DE TRANSPORTE DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 10 June 2008 to 29 July 2023 |
| `ley-de-trasplante-de-organos/` | LEY DE TRASPLANTE DE ORGANOS PARA EL ESTADO DE CAMPECHE | 1 | as first published: 1 January 2008 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE CAMPECHE | 10 | as first published, then each reform: 5 March 2011 to 26 June 2026 |
| `ley-de-uso-de-fuego-en-terrenos-agropecuarios-en-el-estado-d/` | LEY DE USO DE FUEGO EN TERRENOS AGROPECUARIOS EN EL ESTADO DE CAMPECHE | 1 | as first published: 24 July 2015 |
| `ley-de-vialidad-transito-y-control-vehicular/` | LEY DE VIALIDAD, TRANSITO Y CONTROL VEHICULAR DEL ESTADO DE CAMPECHE | 15 | as first published, then each reform: 12 June 2008 to 9 June 2026 |
| `ley-de-vida-silvestre/` | LEY DE VIDA SILVESTRE DEL ESTADO DE CAMPECHE | 1 | as first published: 7 January 2009 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 3 February 2011 to 26 November 2024 |
| `ley-del-archivo-del-poder-legislativo/` | LEY DEL ARCHIVO DEL PODER LEGISLATIVO DEL ESTADO DE CAMPECHE | 1 | oldest version available: 26 July 1998 |
| `ley-del-deporte-y-la-cultura-fisica/` | LEY DEL DEPORTE Y LA CULTURA FISICA PARA EL ESTADO DE CAMPECHE | 10 | as first published, then each reform: 9 July 1998 to 12 February 2026 |
| `ley-del-equilibrio-ecologico-y-proteccion-al-ambiente/` | LEY DEL EQUILIBRIO ECOLOGICO Y PROTECCION AL AMBIENTE DEL ESTADO DE CAMPECHE | 12 | as first published, then each reform: 22 July 1994 to 6 December 2023 |
| `ley-del-instituto-de-la-mujer/` | LEY DEL INSTITUTO DE LA MUJER DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 6 July 2004 to 13 October 2022 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 10 June 2009 to 16 June 2009 |
| `ley-del-patrimonio-cultural/` | LEY DEL PATRIMONIO CULTURAL DEL ESTADO DE CAMPECHE | 1 | as first published: 1 January 2008 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 6 August 2015 to 11 January 2023 |
| `ley-del-premio-estatal-de-periodismo/` | LEY DEL PREMIO ESTATAL DE PERIODISMO DEL ESTADO DE CAMPECHE | 1 | as first published: 5 July 2024 |
| `ley-del-registro-de-centros-de-poblacion/` | LEY DEL REGISTRO DE CENTROS DE POBLACION DEL ESTADO DE CAMPECHE | 8 | as first published, then each reform: 4 April 2008 to 1 November 2026 |
| `ley-del-servicio-de-administracion-fiscal/` | LEY DEL SERVICIO DE ADMINISTRACION FISCAL DEL ESTADO DE CAMPECHE | 5 | as first published, then each reform: 1 April 2017 to 1 January 2024 |
| `ley-del-servicio-profesional-de-carrera-para-la-administraci/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA PARA LA ADMINISTRACION PUBLICA DEL ESTADO DE CAMPECHE | 1 | as first published: 11 December 2019 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE CAMPECHE | 1 | as first published: 1 August 2017 |
| `ley-del-sistema-de-coordinacion-fiscal/` | LEY DEL SISTEMA DE COORDINACION FISCAL DEL ESTADO DE CAMPECHE | 19 | as first published, then each reform: 1 January 2018 to 10 April 2026 |
| `ley-del-sistema-de-informacion/` | LEY DEL SISTEMA DE INFORMACION PARA EL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 1 January 2014 to 10 November 2022 |
| `ley-integral-de-justicia-para-adolescentes-y-medidas-de-reha/` | LEY INTEGRAL DE JUSTICIA PARA ADOLESCENTES Y MEDIDAS DE REHABILITACION Y ASISTENCIA SOCIAL PARA MENORES DE DOCE AÑOS DEL ESTADO DE CAMPECHE | 1 | as first published: 3 December 2014 |
| `ley-integral-para-las-personas-con-discapacidad/` | LEY INTEGRAL PARA LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE CAMPECHE | 16 | as first published, then each reform: 20 July 2012 to 27 March 2025 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE CAMPECHE | 8 | as first published, then each reform: 1 January 2022 to 1 January 2026 |
| `ley-organica-de-la-fiscalia-especializada-en-combate-a-la-co/` | LEY ORGANICA DE LA FISCALIA ESPECIALIZADA EN COMBATE A LA CORRUPCION DEL ESTADO DE CAMPECHE | 1 | as first published: 19 July 2017 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 3 December 2014 to 21 November 2025 |
| `ley-organica-de-la-universidad-autonoma-de-campeche/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE CAMPECHE | 1 | as first published: 20 October 2018 |
| `ley-organica-de-la-universidad-autonoma-del-carmen-antes-uni/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DEL CARMEN -ANTES UNIVERSIDAD DEL CARMEN- | 3 | as first published, then each reform: 30 June 1967 to 18 November 2012 |
| `ley-organica-de-los-municipios/` | LEY ORGANICA DE LOS MUNICIPIOS DEL ESTADO DE CAMPECHE | 22 | as first published, then each reform: 2 April 2008 to 30 July 2026 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 7 June 2020 to 27 October 2022 |
| `ley-organica-del-instituto-campechano/` | LEY ORGANICA DEL INSTITUTO CAMPECHANO | 1 | as first published: 2 February 2010 |
| `ley-organica-del-liceo-carmelita/` | LEY ORGANICA DEL LICEO CARMELITA | 1 | as first published: 25 March 1981 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 14 July 2017 to 12 October 2024 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE CAMPECHE | 19 | as first published, then each reform: 1 October 2012 to 28 July 2026 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 19 July 2017 to 10 April 2021 |
| `ley-organica-del-tribunal-electoral/` | LEY ORGANICA DEL TRIBUNAL ELECTORAL DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 21 November 2016 to 21 July 2017 |
| `ley-para-el-ejercicio-profesional-en-el-estado-de-campeche/` | LEY PARA EL EJERCICIO PROFESIONAL EN EL ESTADO DE CAMPECHE | 1 | as first published: 22 July 2005 |
| `ley-para-el-fomento-de-las-actividades-artesanales-en-el-est/` | LEY PARA EL FOMENTO DE LAS ACTIVIDADES ARTESANALES EN EL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 26 June 2010 to 25 June 2026 |
| `ley-para-el-fomento-de-las-actividades-economicas-y-empresar/` | LEY PARA EL FOMENTO DE LAS ACTIVIDADES ECONOMICAS Y EMPRESARIALES EN EL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 25 December 2001 to 1 June 2023 |
| `ley-para-el-fomento-y-la-participacion-de-las-organizaciones/` | LEY PARA EL FOMENTO Y LA PARTICIPACION DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE CAMPECHE | 1 | as first published: 1 January 2019 |
| `ley-para-el-otorgamiento-de-pensiones-a-beneficiarios-de-int/` | LEY PARA EL OTORGAMIENTO DE PENSIONES A BENEFICIARIOS DE INTEGRANTES DE LAS INSTITUCIONES DE SEGURIDAD PUBLICA DEL ESTADO E INTEGRANTES DE LAS FUERZAS ARMADAS DE MEXICO FALLECIDOS EN CUMPLIMIENTO DE SU DEBER DENTRO DEL TERRITORIO DEL ESTADO DE CAMPECHE | 1 | as first published: 3 January 2012 |
| `ley-para-el-otorgamiento-del-premio-al-merito-medico/` | LEY PARA EL OTORGAMIENTO DEL "PREMIO AL MERITO MEDICO DEL ESTADO DE CAMPECHE" | 1 | as first published: 26 November 2021 |
| `ley-para-la-administracion-y-destino-de-bienes-asegurados-ab/` | LEY PARA LA ADMINISTRACION Y DESTINO DE BIENES ASEGURADOS, ABANDONADOS O DECOMISADOS Y DESTINO DE BIENES DECLARADOS EXTINTOS Y DE SANCIONES ECONOMICAS POR HECHOS DE CORRUPCION PARA EL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 31 October 2024 to 30 July 2026 |
| `ley-para-la-declaracion-especial-de-ausencia-por-desaparicio/` | LEY PARA LA DECLARACION ESPECIAL DE AUSENCIA POR DESAPARICION DE PERSONAS DEL ESTADO DE CAMPECHE | 1 | as first published: 17 December 2025 |
| `ley-para-la-gestion-integral-de-los-residuos-solidos-urbanos/` | LEY PARA LA GESTION INTEGRAL DE LOS RESIDUOS SOLIDOS URBANOS, DE MANEJO ESPECIAL Y PELIGROSO DEL ESTADO DE CAMPECHE | 4 | as first published, then each reform: 3 April 2008 to 4 July 2022 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE CAMPECHE | 14 | as first published, then each reform: 19 July 2007 to 11 July 2026 |
| `ley-para-la-prevencion-del-sobrepeso-y-la-obesidad-en-el-est/` | LEY PARA LA PREVENCION DEL SOBREPESO Y LA OBESIDAD EN EL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 6 May 2021 to 5 December 2024 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 29 November 2014 to 2 June 2022 |
| `ley-para-la-proteccion-de-sujetos-en-situacion-de-riesgo-en/` | LEY PARA LA PROTECCION DE SUJETOS EN SITUACION DE RIESGO EN EL PROCEDIMIENTO PENAL DEL ESTADO DE CAMPECHE | 2 | as first published, then each reform: 3 December 2014 to 9 May 2015 |
| `ley-para-la-proteccion-y-bienestar-de-los-animales/` | LEY PARA LA PROTECCION Y BIENESTAR DE LOS ANIMALES DEL ESTADO DE CAMPECHE | 7 | as first published, then each reform: 1 January 2019 to 11 April 2026 |
| `ley-para-la-venta-ordenada-y-consumo-responsable-de-bebidas/` | LEY PARA LA VENTA ORDENADA Y CONSUMO RESPONSABLE DE BEBIDAS ALCOHOLICAS DEL ESTADO DE CAMPECHE | 6 | as first published, then each reform: 24 September 2015 to 30 December 2025 |
| `ley-para-prevenir-y-combatir-la-trata-de-personas/` | LEY PARA PREVENIR Y COMBATIR LA TRATA DE PERSONAS DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 1 January 2024 to 18 August 2025 |
| `ley-para-prevenir-y-sancionar-la-tortura-en-el-estado-de-cam/` | LEY PARA PREVENIR Y SANCIONAR LA TORTURA EN EL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 12 November 1993 to 23 July 2012 |
| `ley-para-prevenir-combatir-y-sancionar-toda-forma-de-discrim/` | LEY PARA PREVENIR, COMBATIR Y SANCIONAR TODA FORMA DE DISCRIMINACION EN EL ESTADO DE CAMPECHE | 15 | as first published, then each reform: 3 August 2007 to 1 August 2024 |
| `ley-para-restringir-el-acceso-de-menores-de-edad-a-publicaci/` | LEY PARA RESTRINGIR EL ACCESO DE MENORES DE EDAD A PUBLICACIONES Y GRABACIONES EN MEDIOS IMPRESOS AUDIOVISUALES Y SERVICIOS DE INTERNET CON CONTENIDO PARA ADULTOS EN EL ESTADO DE CAMPECHE | 1 | as first published: 25 January 2008 |
| `ley-que-crea-el-premio-al-merito-policial/` | LEY QUE CREA EL "PREMIO AL MERITO POLICIAL" DEL ESTADO DE CAMPECHE | 1 | as first published: 28 July 2017 |
| `ley-que-crea-el-premio-campeche/` | LEY QUE CREA EL "PREMIO CAMPECHE" | 3 | as first published, then each reform: 21 March 2013 to 7 May 2025 |
| `ley-que-crea-el-colegio-de-bachilleres/` | LEY QUE CREA EL COLEGIO DE BACHILLERES DEL ESTADO DE CAMPECHE | 3 | as first published, then each reform: 8 September 1990 to 13 March 2014 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Merida, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
