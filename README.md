# tarjeta.carella.mx

Página pública de la tarjeta de lealtad de Carella (QR del mostrador).

- Sin `?t=`: registro (nombre, celular, aviso de privacidad).
- Con `?t=<token>`: la tarjeta con su QR y el botón para Apple Wallet.

Toda la lógica vive en la Edge Function `wallet` de Supabase
(repo `carella-admin`, `supabase/functions/wallet`). Aquí no hay llaves.
