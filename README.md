# Aviso de Riesgo de Corte — Generador para correo (Cobranza MX)

Copia del generador de estado de cuenta, adaptada para el correo de **riesgo de corte / desactivación por no pago**. Herramienta de una sola página (`index.html`, sin dependencias).

## Cómo se usa
1. **Pega la cartera** copiada desde Excel (mismo formato que el estado de cuenta). Solo se toman las facturas **vencidas** a la fecha de corte; las vigentes, canceladas y pagadas quedan fuera.
2. **Marca las razones sociales del cliente**, revisa la fecha de corte y la **fecha de desactivación del servicio**.
3. **Revisa las facturas vencidas** (desmarca las que no quieras incluir; completa abonos si aplica).
4. **Copiar para pegar en el correo** → pega en Outlook/Gmail.

En el texto del correo, `{desactivacion}` se reemplaza por la fecha de desactivación, `{fecha}` por la fecha de corte y `{vencido}` por el total vencido.

URL: https://fdurancontreras4-ui.github.io/riesgo-corte/

> Los datos de la cartera no se suben a ningún lado: todo se procesa en el navegador.
