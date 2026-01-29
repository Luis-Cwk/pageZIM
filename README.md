# Entropia Agent - ERC-8004 Registration

Este repositorio contiene los archivos de registro para el agente **Entropia**, un asesor financiero creativo para artistas NFT.

## 📁 Archivos Incluidos

1. **agent-registration.json** - Archivo de registro ERC-8004 (el que necesitas para la URL)
2. **entropia-system-prompt.md** - Prompt mejorado y adaptable del agente
3. **README.md** - Este archivo

## 🚀 Cómo Subir a GitHub Pages (paso a paso)

### Paso 1: Crear repositorio en GitHub
1. Ve a https://github.com
2. Haz clic en el botón "+" arriba a la derecha → "New repository"
3. Nombre del repositorio: `entropia-agent`
4. Marca "Public"
5. Marca "Add a README file"
6. Clic en "Create repository"

### Paso 2: Subir archivos
1. En tu nuevo repositorio, clic en "Add file" → "Upload files"
2. Arrastra estos archivos:
   - `agent-registration.json`
   - `entropia-system-prompt.md`
3. Clic en "Commit changes"

### Paso 3: Activar GitHub Pages
1. En tu repositorio, ve a "Settings"
2. En el menú izquierdo, busca "Pages"
3. En "Source", selecciona "main" branch
4. Clic en "Save"
5. Espera 1-2 minutos

### Paso 4: Obtener tu URL
Tu archivo estará disponible en:
```
https://TU-USUARIO.github.io/entropia-agent/agent-registration.json
```

**Esta es la URL que debes poner en Agentscan** ☝️

## 🔧 Personalización

### Actualizar el JSON antes de subir:

1. Abre `agent-registration.json`
2. Reemplaza:
   - `"image": "https://example.com/entropia-agent.png"` → URL de tu imagen/logo
   - `"endpoint": "https://tu-usuario.github.io/entropia-agent/"` → Tu usuario real de GitHub
   - `"agentId": 0` → El ID que te dé Agentscan después de registrar
   - `"agentRegistry": "eip155:11155111:0xYourRegistryAddress"` → La dirección del registry que uses

### Agregar tu imagen del agente (opcional):
1. Sube una imagen (entropia-logo.png) a tu repositorio
2. Tu URL de imagen será: `https://TU-USUARIO.github.io/entropia-agent/entropia-logo.png`

## 📝 Notas Importantes

- **ANTES** de registrar en Agentscan, asegúrate de que tu archivo JSON esté públicamente accesible
- Prueba tu URL en el navegador: debería mostrar el JSON
- Después de registrar, actualiza el `agentId` en el JSON con el ID real que te asignen
- El prompt en `entropia-system-prompt.md` es para que lo uses al configurar tu agente AI

## 🆘 Problemas Comunes

**Error: Archivo no encontrado**
- Verifica que GitHub Pages esté activado
- Espera 2-3 minutos después de activarlo
- Asegúrate de escribir exactamente el nombre del archivo

**JSON no se ve bien**
- GitHub Pages puede tardar en actualizar
- Limpia el caché del navegador (Ctrl+Shift+R)
- Verifica que el archivo no tenga errores de sintaxis

## 🔗 Enlaces Útiles

- [Documentación ERC-8004](https://eips.ethereum.org/EIPS/eip-8004)
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [Agentscan](https://agentscan.xyz)

---

Creado con ❤️ para artistas Web3
