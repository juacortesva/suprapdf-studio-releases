<div align="center">
  <img src="assets/icon.png" alt="SupraPDF Studio" width="120" height="120" />
  <h1>SupraPDF Studio</h1>
  <p><strong>Official Public Releases & Binary Distribution</strong></p>

  <p>
    <a href="https://github.com/juacortesva/suprapdf-studio-releases/releases/tag/v1.1.0"><img src="https://img.shields.io/badge/Release-v1.1.0%20Onyx-22C55E?style=for-the-badge&logo=windows" alt="Release" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License MIT" /></a>
    <a href="https://github.com/juacortesva/suprapdf-studio-releases/releases"><img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-0078D6?style=for-the-badge&logo=windows11" alt="Platform" /></a>
    <a href="https://github.com/juacortesva/suprapdf-studio-releases"><img src="https://img.shields.io/badge/Privacy-100%25%20Offline%20%2F%20Air--Gapped-10B981?style=for-the-badge" alt="Offline" /></a>
  </p>
</div>

---

Repositorio oficial y portal público de distribución de binarios certificados de **SupraPDF Studio**, la suite integral de productividad documental para Windows diseñada para la soberanía absoluta de datos y ejecución local desacoplada.

---

## 📥 Descargas Oficiales — Versión 1.1.0 "Onyx" (2026)

| Formato de Distribución | Tamaño | Arquitectura | Enlace de Descarga Directa |
| :--- | :--- | :--- | :--- |
| **Instalador Oficial (Setup)** | 111.68 MB | Windows x64 | [⬇ Descargar Setup (`.exe`)](https://github.com/juacortesva/suprapdf-studio-releases/releases/download/v1.1.0/SupraPDF_Studio_Setup_v1.1.0_Onyx.exe) |
| **Paquete Portable (.zip)** | 161.80 MB | Windows x64 | [⬇ Descargar Portable (`.zip`)](https://github.com/juacortesva/suprapdf-studio-releases/releases/download/v1.1.0/SupraPDF_Studio_v1.1.0_Onyx_Portable.zip) |

---

## 🔒 Sumas de Verificación e Integridad (SHA-256 Checksums)

Para verificar la integridad criptográfica y autenticidad de los archivos descargados, compare el hash generado localmente mediante PowerShell (`Get-FileHash -Algorithm SHA256 <archivo>`) con los valores oficiales certificados:

| Archivo de Release | Tamaño | Hash SHA-256 Verificado |
| :--- | :--- | :--- |
| `SupraPDF_Studio_Setup_v1.1.0_Onyx.exe` | 111.68 MB | `7DC78C12A573118BBC274CD2BB3607D59C9F2AF97246276529FEF26B202697FE` |
| `SupraPDF_Studio_v1.1.0_Onyx_Portable.zip` | 161.80 MB | `D80903D7147C13BC2BF86CA1FC743342B9302980EB91A62BDD22F3008C3902EC` |

### Verificación rápida en PowerShell:
```powershell
# Para el instalador Setup:
(Get-FileHash .\SupraPDF_Studio_Setup_v1.1.0_Onyx.exe -Algorithm SHA256).Hash -eq "7DC78C12A573118BBC274CD2BB3607D59C9F2AF97246276529FEF26B202697FE"

# Para la versión Portable:
(Get-FileHash .\SupraPDF_Studio_v1.1.0_Onyx_Portable.zip -Algorithm SHA256).Hash -eq "D80903D7147C13BC2BF86CA1FC743342B9302980EB91A62BDD22F3008C3902EC"
```

---

## 🚀 Novedades de la Versión 1.1.0 "Onyx"

- **Nuevo Motor de Compresión Inteligente de PDF:** Reducción drástica del tamaño de archivos mediante optimización de flujos binarios Deflate y remuestreo bicúbico adaptativo de imágenes con perfiles calibrados (Máxima compresión, Equilibrada, Alta fidelidad), preservando vectores, tipografías y estructura sin artefactos destructivos.
- **Evolución y Pulido Visual de Interfaz (UI/UX):** Interfaz limpia y estilizada libre de tecnicismos oscuros y códigos hexadecimales crudos en etiquetas, selector de temas y paleta cromática unificada Onyx (grafito/obsidiana con acentos esmeralda), y rediseño de `FirstRunDialog` con bordes redondeados verdaderos y barra de título integrada.
- **Extracción Nativa Lossless de Imágenes:** Extracción fidedigna de streams binarios XObjects directamente a carpeta o empaquetado automático en ZIP con barra de progreso asíncrona y sin recompresión.
- **Módulo Dedicado de Reparación de PDF:** Reconstrucción estructural y física de tablas de referencias cruzadas (`xref`) corruptas, flujos binarios y árboles de páginas rotos como herramienta de primer nivel.
- **Internacionalización Hexagonal Reactiva en 6 Idiomas:** Paridad estricta al 100% y cambio en caliente entre Español, Inglés, Francés, Portugués, Ruso y Chino Simplificado.
- **Sistema Dinámico FIFO de «Herramientas Recientes»:** Pantalla de inicio interactiva con rastreador dinámico de las funciones más utilizadas.
- **Visor PDF Nativo Vectorial:** Motor de alta precisión con modos de página, miniaturas y buscador de texto integrado sin dependencias pesadas.
- **Pestaña de Metadatos Documentales:** Inspección y purga forense de información confidencial y propiedades de autoría.
- **Comparador Visual de Documentos:** Detección lado a lado de discrepancias visuales y estructurales entre PDFs.
- **Editor Visual Enriquecido:** Sellos, formas geométricas vectoriales y firmas manuscritas con remoción inteligente de fondo blanco.

---

## 🛡️ Compromiso de Privacidad Absoluta (100% Offline / Air-Gapped)

- **Cero Telemetría y Cero Nube:** SupraPDF Studio no transmite datos, métricas ni telemetría a servidores remotos.
- **Procesamiento Exclusivo en CPU/RAM Local:** Todas las operaciones (NLU, compresión, extracción, criptografía y renderizado) se procesan estrictamente en la memoria del dispositivo.
- **Aislamiento Seguro:** Totalmente apto para operar en redes cerradas, entornos corporativos restringidos y estaciones de trabajo desconectadas (*Air-Gapped*).

---

## 📄 Licencia

Este software se distribuye bajo la licencia [MIT](LICENSE) (o consulte en [Open Source Initiative](https://opensource.org/licenses/MIT)). Copyright © 2026 Juan David Cortés Vaca.
