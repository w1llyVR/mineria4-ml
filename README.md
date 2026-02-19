# 🛠️ Minería 4.0 — ML Diplomado

> Repositorio de machine learning para el Diplomado en Minería 4.0.

---

## 🚀 Instalación y configuración

### 1. Clonar el repositorio

```bash
git clone https://github.com/w1llyVR/mineria4-ml.git
cd mineria4-ml
```

### 2. Crear el entorno virtual

```bash
python -m venv .venv
```

### 3. Activar el entorno virtual

**Windows (CMD):**
```cmd
.venv\Scripts\activate
```

**Windows (PowerShell):**
```powershell
.venv\Scripts\Activate.ps1
```

**macOS / Linux:**
```bash
source .venv/bin/activate
```

### 4. Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## ⚠️ Nota para usuarios de Windows

Si encuentras errores relacionados con rutas de archivo demasiado largas, habilita el soporte de rutas largas ejecutando el siguiente comando en **PowerShell como Administrador**:

```powershell
New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" `
  -Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force
```

Luego reinicia el equipo y repite la instalación.

---

## 📁 Estructura del proyecto

```
mineria4-ml/
├── .venv/               # Entorno virtual (no incluido en el repo)
├── requirements.txt     # Dependencias del proyecto
└── README.md
```

---

## 📄 Licencia

Este proyecto es parte del Diplomado en Minería 4.0.