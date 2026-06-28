cat > README.md << 'EOF'
# UniCal - Calendario Unificado Privado

Aplicación open source para integrar **todas tus cuentas** (iCloud múltiple, Gmail, Outlook) en una sola vista intuitiva y segura.

## Características
- Vista unificada de múltiples calendarios
- Enfoque en privacidad y seguridad
- Fácil de usar en Mac e iPhone
- Open Source

## Cuentas configuradas
- 11 cuentas iCloud (davidpeces@...)
- Cuentas Gmail
- Cuentas Outlook / Exchange

## Cómo conectar tus cuentas

### 1. iCloud (recomendado primero)
1. Ve a [appleid.apple.com](https://appleid.apple.com)
2. Inicia sesión y ve a **Contraseñas específicas de apps**
3. Crea una nueva contraseña llamada "UniCal"
4. En UniCal usa:
   - Servidor: `https://caldav.icloud.com`
   - Usuario: tu email completo (ej: davidpeces.crypto@icloud.com)
   - Contraseña: la que generaste

### 2. Gmail / Google
- Usa OAuth2 (Conectar con Google) – muy seguro.

### 3. Outlook / Exchange
- Usa OAuth2 con cuenta Microsoft.

## Cómo usar
1. Abre `unical.html` o la versión completa.
2. Añade eventos → se integran en la vista unificada.
3. Disfruta de una sola agenda clara.

---

**Licencia**: MIT  
**Privacidad**: Tus datos permanecen bajo tu control.

¡Bienvenido a tu agenda unificada!

git add README.md
git commit -m "Añadido README con instrucciones detalladas"
git push origin main
