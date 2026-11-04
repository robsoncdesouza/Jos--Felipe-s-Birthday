# Convite de aniversário — José Felipe

Página web de convite para comemorar o primeiro aniversário do José Felipe. O site apresenta os detalhes da festa e permite que os convidados abram a rota no Google Maps ou confirmem presença pelo WhatsApp.

## Conteúdo do convite

- Aniversário de 1 ano, em **26/11**, às **12h30**.
- Endereço: **Rua Laranjeiras, 193 — Tanque Caio, Ribeirão Pires - SP, 09435-490**.
- Link para consultar a localização no Google Maps.
- Botão de confirmação de presença que abre uma conversa no WhatsApp com uma mensagem preenchida.

## Tecnologias

- HTML5
- CSS3
- JavaScript nativo

Não há dependências, etapa de compilação ou processo de instalação.

## Como visualizar

Abra `index.html` diretamente em um navegador. Se preferir, sirva a pasta do projeto com qualquer servidor HTTP estático.

## Estrutura do projeto

```text
.
├── index.html       # Conteúdo, detalhes da festa e links de ação
├── styles.css       # Layout e estilos responsivos
├── script.js        # Animações de entrada dos elementos
├── img/
│   ├── chefinho.png
│   ├── chefinho2.png
│   └── mala-destaque.png
└── assets/          # Pasta disponível para recursos adicionais
```

As animações de entrada respeitam a preferência do sistema por movimento reduzido e mantêm o conteúdo visível quando o navegador não oferece suporte a `IntersectionObserver`.

## Atualização das informações

Os textos do convite, a data, o horário, o endereço e os links do Google Maps e do WhatsApp estão em `index.html`. Para alterar a mensagem automática ou o destino da confirmação, atualize o link `wa.me` nessa página. Os estilos ficam em `styles.css`, e o comportamento das animações fica em `script.js`.
