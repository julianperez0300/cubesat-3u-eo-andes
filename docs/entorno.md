# Entorno de desarrollo

Fecha de configuración: 2026-10-10

## Sistema
- Sistema operativo: Windows 10
- Terminal: Windows PowerShell

## Control de versiones
- Git: 2.56.0.windows.2
- GitHub CLI: 2.102.0

## Python
- Python: 3.12.10
- Entorno virtual: `.venv` (no se sube a Git)
- Dependencias exactas: ver `requirements.txt`
- Librerías principales: numpy 2.5.3, scipy 1.18.1, astropy 8.0.1, matplotlib 3.11.2, pandas 3.0.6

## Análisis de misión
- GMAT: R2026a
  (instalado fuera del repositorio, en `Desktop\GMAT`)
  Los avisos de MATLAB al abrir son normales: no se usa MATLAB.

## CAD
- KOMPAS-3D: versión 24.0.1.2800
- Formato de intercambio: STEP
- Respaldo/visor: FreeCAD (opcional, aún sin instalar)

## Cómo retomar el trabajo
1. Abrir PowerShell.
2. `cd "$([Environment]::GetFolderPath('Desktop'))\cubesat-3u-eo-andes"`
3. `.venv\Scripts\Activate.ps1`
4. `git status`

## Pendientes
- [ ] Prueba KOMPAS → STEP → FreeCAD con cubo de 100 mm