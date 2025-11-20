# PlataformaSentidos

Plataforma para crear, generar y vender contenidos digitales (micro-libros, guías, audiolibros, cápsulas) en múltiples idiomas y formatos.

Este proyecto usa:

- Next.js (frontend + backend)
- Supabase (base de datos, auth, storage)
- OpenAI (IA para texto y audio)
- Stripe / PayPal (pagos, a definir)
- Pandoc (para generar PDF / ePub, más adelante)

---

## 1. Requisitos

- Node.js 18 o superior
- Cuenta en:
  - Supabase
  - OpenAI
  - (opcional por ahora) Stripe o PayPal

---

## 2. Instalación

Clonar el repo:

```bash
git clone https://github.com/raulfcarbone/plataformasentidos.git
cd plataformasentidos

npm install
