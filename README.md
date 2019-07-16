# l10n_mx_data
 Data needed for Mexico's CFDI (EDI) localization (OCA) v3.3 and later.<br>
 \[$og  V1_04  2019-07-16\]

## Contents:<br>

######	Carpetas:
	cat		Catálogos en Excel (.XLSX individualizados por tabla y .XLS originales del SAT)
	cpl		Ayudas y documentos técnicos de cada Complemento
	wrk		Documentos de trabajo para la Localización
	    ade		    Addendas
	    ant		    Anticipos
	    can		    Cancelaciones
	    cfd		    CFDI
	    cnn		    Conectores
	    err		    Errores
	    ncr		    Nota de Crédito
	    pac		    PACs
	    rtn		    Retenciones
	    trs		    Traslado
	    wbs		    WebServices
	xml		Archivos XLST, XSD y ejemplos XML de CFDIs y complementos

###### Complementos
	
	acc	Enajenación de Acciones
	aer	Aerolíneas
	art	Obras de Arte Plásticas y Antigüedades
	cce	Comercio Exterior
	cfd	CFDI Registro fiscal
	cmb	Consumo de Combustibles
	coo	Persona Física integrante de Coordinados
	des	Certificado de Destrucción
	det	Sector de Ventas al Detalle
	div	Compra Venta de Divisas
	don	Donatarias
	drv	Operaciones con Derivados
	ecc	Estado de cuenta de combustibles monederos electrónicos
	esp	Pago en especie
	fid	Arrendamiento en Fideicomiso
	fin	Sector Financiero
	hdr	Hidrocarburos
	hip	Intereses Hipotecarios
	ine	INE (Instituto Nacional Electoral)
	int	Intereses por Rendimiento de Inversiones
	ley	Leyendas fiscales
	loc	Otros derechos e impuestos locales
	nom	Recibo de pago de Nóminas*
	not	Notarios públicos
	pag	Recepción de Pagos*
	pex	Pagos a Extranjeros
	pre	Premios
	ret	Planes de Retiro
	rsv	Renovación y sustitución de vehículos
	spc	Servicios Parciales de Construcción
	spe	SPEI de tercero a tercero
	spt	Servicios de Plataformas Tecnológicas
	tfd	Timbre Fiscal Digital
	tur	Turista pasajero extranjero
	usd	Vehículo Usado
	val	Vales de Despensa

	Complementos Concepto:
		ter	Terceros
		edu	Instituciones educativas privadas
		iep	Acreditamiento del IEPS
		nue	Venta de vehículos nuevos

######	Catálogos:

	c_Actividad.xlsx				hdr
	c_Aduana.xlsx					hdr	tfd
	c_Banco.xlsx					nom
	c_ClavePagoPedimento.xlsx			hdr
	c_ClavePedimento.xlsx				cce	hdr
	c_ClaveProdServ.xlsx				cfd
	c_ClaveTipoCombustible.xlsx			ecc	cmb
	c_ClaveUnidad.xlsx				cfd	tfd
	c_CodigoPostal.xlsx				cce	cfd
	c_Colonia.xlsx					cce
	c_CveRetenc					spt
	c_EntidadesFederativas				spt
	c_Estado.xlsx					cce
	c_FormaPago.xlsx				cfd	pag	tfd
	c_FormaPagoServ.xlsx				spt
	c_FraccionArancelaria.xlsx			cce
	c_Impuesto.xlsx					cfd	pag
	c_INCOTERM.xlsx					cce
	c_Localidad.xlsx				cce
	c_Mes.xlsx					hdr
	c_MetodoPago.xlsx				cfd	pag
	c_Moneda.xlsx					cfd	pag
	c_MotivoTraslado.xlsx				cce
	c_Municipio.xlsx				cce
	c_NumPedimentoAduana.xlsx			hdr	tfd
	c_OrigenRecurso.xlsx				nom
	c_Periodicidad					spt
	c_Paises.xlsx					spt
	c_Pais.xlsx					cce	cfd
	c_PatenteAduanal.xlsx				hdr	tfd
	c_PeriodicidadPago.xlsx				nom
	c_RangoMenRet.xlsx				spt
	c_RangoSemRet.xlsx				spt
	c_RegimenFiscal.xlsx				cfd
	c_RiesgoPuesto.xlsx				nom
	c_SubActividad.xlsx				hdr
	c_SubTipoServ.xlsx				spt
	c_Tarea.xlsx					hdr
	c_TasaCuota.xlsx				spt
	c_TasaOCuota.xlsx				pag	tfd
	c_TipoAportODep.xlsx				ret
	c_TipoCadenaPago.xlsx				pag
	c_TipoContrato.xlsx				nom
	c_TipoContribuyenteSujetoRetenc			spt
	c_TipoDeComprobante.xlsx			cfd
	c_TipoDeduccion.xlsx				nom
	c_TipoDeImpuesto				spt
	c_TipoDeServ.xlsx				spt
	c_TipoDividendoUtilidadDistrib			spt
	c_TipoFactor.xlsx				cfd	pag
	c_TipoHoras.xlsx				nom
	c_TipoImpuesto					spt
	c_TipoIncapacidad.xlsx				nom
	c_TipoJornada.xlsx				nom
	c_TipoNomina.xlsx				nom
	c_TipoOperacion.xlsx				cce
	c_TipoOtroPago.xlsx				nom
	c_TipoPercepcion.xlsx				nom
	c_TipoRegimen.xlsx				nom
	c_TipoRelacion.xlsx				cfd
	c_TipoSerie.xlsx				des
	c_UnidadAduana.xlsx				cce
	c_UsoCFDI.xlsx					cfd

	Pendientes:
		c_CaracterísticasDeObraoPieza.xlsx	art
		c_TAR.xlsx				iep
		c_TipoBien.xlsx				art
		c_TipoDecreto.xlsx			rsv
		c_TipoVehiculo_r.xlsx			rsv
		c_TipoVehiculo_s.xlsx			rsv
		c_TituloAdquirido.xlsx			art
		c_VehiculoEnajenado.xlsx		rsv

###### Links:
- [Anexo 20](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/anexo_20_version3-3.htm)
- [XSD](http://www.sat.gob.mx/sitio_internet/cfd/3/cfdv33.xsd)
- [Tipos](http://omawww.sat.gob.mx/sitio_internet/cfd/tipoDatos/tdCFDI/tdCFDI.xsd)
- [XSLT](http://www.sat.gob.mx/sitio_internet/cfd/3/cadenaoriginal_3_3/cadenaoriginal_3_3.xslt)
- [Combustible](http://www.sat.gob.mx/sitio_internet/cfd/EstadoDeCuentaCombustible/ecc11.xsd)
- [PACs](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/proveedores_autorizados_certificacion.htm)
- [CFDI](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/catCFDI.xls)
- [Nómina](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/catNomina.xls)
- [Pedimento](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_ClavePedimento.xls)
- [Colonia](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_Colonia.xls)
- [Pagos](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/catPagos.xls)
- [Fraccion Arancelaria](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_FraccionArancelaria.xls)
- [INCOTERM](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_INCOTERM.xls)
- [Localidad](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_Localidad.xls)
- [Motivo Traslado](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_MotivoTraslado.xls)
- [Municipio](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_Municipio.xls)
- [TipoOperacion](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_TipoOperacion.xls)
- [UnidadAduana](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_UnidadAduana.xls)
- [UnidadMedidaAduana](http://omawww.sat.gob.mx/tramitesyservicios/Paginas/documentos/c_UnidadMedidaAduana.xls)

###### Notas:
	(1)	Los complementos identificados con * siguen apareciendo en el apartado 
		de complementos, aunque la guía del anexo 20 de la versión 3.3, ahora indica
		que son un tipo de CFDI.  
		Fuente: https://contadormx.com/2017/09/04/cfdi-complemento-obligatorio-sat
	(2)	Se están integrando los archivos de datos, en vez de las ligas, porque
		están cambiando la estructura del sitio web del SAT y se han estado perdiendo
		ligas... habrá que mantenerlos actusptzados manualmente, mientras se
		estabiliza el sitio.
		
###### Estructura simplificada del XML (cfdv33.xsd) del cfdi:

	Tipos de Campo:
	s[#]	Alfanumérico con # posiciones
	s[]	Alfanumérico sin # de posiciones especificado
	e[#]	Numérico entero con   # posiciones
	f[#.%] 	Numérico flotante con # posiciones y % decimales
	f[]	Numérico flotante sin # de posiciones especificado
	d[#]	Fecha con # posiciones
	u[#]	UUID  con # posiciones
	v[3.3]	Numérico flotante con valor 3.3 (versión del CFDI)
	{}	Grupo de datos repetible
			
	cfdi:

		Comprobante
			{
				CfdiRelacionado
					{
						UUID                                                        u[36]
					}
					TipoRelacion                                                        e[2]
				
				Emisor
					Rfc                                                                 s[13]
					Nombre                                                              s[254]
					RegimenFiscal                                                       e[3]
					
				Receptor
					Rfc                                                                 s[13]
					Nombre                                                              s[254]
					ResidenciaFiscal                                                    s[3]
					NumRegIdTrib                                                        s[40]
					UsoCFDI                                                             s[3]
					
				Conceptos
					{
					   Concepto
						{
						   Impuestos
							{
							   Traslados
								{
								   Traslado
									Base                                f[8.6]
									Impuesto                            e[3]
									TipoFactor                          s[7]
									TasaOCuota                          f[8.6]
									Importe                             f[]
								}
											 
							   Retenciones
								{
								   Retención
									Base                                f[8.6]
									Impuesto                            e[3]
									TipoFactor                          s[7]
									TasaOCuota                          f[8.6]
									Importe                             f[]
								}
							}
									 
								InformacionAduanera
									NumeroPedimento                     e[21]
									
								CuentaPredial
									Numero                              s[150]
									
								{
									ComplementoConcepto                 s[]
								}
								 
								Parte
									{
										InformacionAduanera
											NumeroPedimento     e[21]
									}
									 
									ClaveProdServ                       e[8]
									NoIdentificacion                    s[100]
									Cantidad                            f[8.6]
									Unidad                              s[20]
									Descripcion                         s[1000]
									ValorUnitario                       f[]
									Importe                             f[]
							}
							ClaveProdServ                                       e[8]
							NoIdentificacion                                    s[100]
							Cantidad                                            f[8.6]
							ClaveUnidad                                         e[3]
							Unidad                                              s[20]
							Descripcion                                         s[1000]
							ValorUnitario                                       f[]
							Importe                                             f[]
							Descuento                                           f[]
					}
					Impuestos
					{
						Retenciones
							{
								Retención
									Impuesto                            e[3]
									Importe                             f[]
							}
							Traslados
							{
								Traslado
									Impuesto                            e[3]
									TipoFactor                          s[7]
									TasaOCuota                          f[8.6]
									Importe                             f[]
							}
					}
					
					TotalImpuestosRetenidos                                             f[]
					TotalImpuestosTrasladados                                           f[]
				
				{
					Complemento                                                         s[]
				}
					{
					Addenda                                                             s[]
				}
				
			}
			
			Version                                                                             v[3.3]
			Serie                                                                               s[25]
			Folio                                                                               s[40]
			Fecha                                                                               d[19]
			Sello                                                                               s[]
			FormaPago                                                                           e[2]
			NoCertificado                                                                       s[20]
			Certificado                                                                         s[]
			CondicionesDePago                                                                   s[1000]
			SubTotal                                                                            f[]
			Descuento                                                                           f[]
			Moneda                                                                              s[3]
			TipoCambio                                                                          f[8.6]
			Total                                                                               f[]
			TipoDeComprobante                                                                   s[1]
			MetodoPago                                                                          s[3]
			LugarExpedicion                                                                     e[5]
			Confirmacion                                                                        s[5]


## Disclaimer:<br>
_This repository contains public information from several sources.  Although it's preferable to link them to the original source to minimize document maintenance, we found that the Mexican government tax agency (SAT) recently modified its pages creating a number of broken links along related websites.<br>
To facilitate this development, we searched for documents that contribute with something relevant and included them physically in this repository.<br>
Despite our efforts to use only original and truthful sources, in addition to keeping the repository updated, over time there may be changes or inconsistencies that we still haven't noticed, so the information is publicly offered "as is", without a link or any other kind of legal obligation on our part.<br>
Because this repository contains public information as guidance only, taken from public sites like SAT or third parties, some documents contain logos and / or formats that are the property of the original owner;  We hereby endorse our respect for copyright and therefore we have retained its original format, which includes the source.  We'll be glad to receive any update, comment or indication about, and act accordingly our mutual interests._

