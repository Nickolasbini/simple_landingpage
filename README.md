# 💼 Landing Page - Cervo Digital

Uma landing page moderna e responsiva feita com **HTML puro**, **Tailwind CSS via CDN** e **EmailJS** para envio de mensagens. Ideal como base para agências, freelancers ou negócios locais que desejam uma presença digital profissional com carregamento rápido e visual limpo.

---

## ✨ Recursos

- ✅ Layout responsivo e adaptado para mobile
- 🎨 Design limpo e moderno com Tailwind CSS
- 📨 Formulário funcional de contato usando EmailJS
- 🔗 Navegação suave entre seções
- ⚡️ Sem dependência de frameworks: puro HTML + Tailwind

---

## 📁 Estrutura

```
/
├── index.html       → Página principal com Tailwind via CDN
├── /imagens         → Imagens utilizadas (ícones, banners, etc.)
└── README.md        → Este arquivo
```

> Obs: Não há uso de JS externo além do EmailJS, tornando o projeto leve e fácil de adaptar.

---

## 📬 Como configurar o EmailJS

Para que o formulário funcione:

1. Acesse https://www.emailjs.com
2. Crie uma conta gratuita
3. Obtenha seu:
   - **User ID**
   - **Service ID**
   - **Template ID**
4. Substitua no `<script>` do final do `index.html`:

```js
emailjs.init('userId');
emailjs.sendForm('serviceId', 'templateId', this)
```

---

## 🛠️ Tecnologias usadas

- Tailwind CSS via CDN
- EmailJS
- HTML5 + CSS3

---

## 🚀 Como usar

Clone este repositório:

```bash
git clone https://github.com/SeuUsuario/landing-page-tailwind
```

Abra o `index.html` no seu navegador

(Opcional) Configure o EmailJS para ativar o formulário de contato

---

## 📌 Licença

Este projeto está licenciado sob a MIT License.  
Sinta-se livre para usar, modificar e distribuir.