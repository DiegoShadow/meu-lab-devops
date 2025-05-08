# 📱 1. Calculadora Padrão (Standard)
# Imagine estar usando uma calculadora física com botões brilhantes e responsivos, mas com um visual futurista. Nessa aba você pode:
# 
# Realizar operações básicas: adição (+), subtração (−), multiplicação (×), divisão (/)
# 
# Usar botões funcionais como:
# 
# AC (All Clear) — zera tudo
# 
# CE (Clear Entry) — apaga só a entrada atual
# 
# % — calcula porcentagem
# 
# . — adiciona ponto decimal
# 
# = — realiza o cálculo da expressão
# 
# Tudo é exibido em um visor digital estilizado, com fonte "Orbitron" e efeito de brilho cibernético.
# 
# Também há suporte a teclado físico: você pode digitar os números e operadores diretamente.
# 
# 💱 2. Conversor de Moedas (Currency)
# Ao clicar na aba “Currency”, a interface muda para um painel de conversão de moedas. Funcionalidade:
# 
# O usuário informa:
# 
# Valor a converter
# 
# Moeda de origem (ex: USD)
# 
# Moeda de destino (ex: BRL)
# 
# Clica no botão Convert e recebe o resultado da conversão, além da taxa usada (com base em valores estáticos no próprio código – ou seja, não atualiza automaticamente via internet).
# 
# As moedas disponíveis incluem: Dólar Americano, Euro, Libra, Iene, Real, Dólar Canadense, Dólar Australiano e Yuan.
# 
# 🎨 Design e Estilo
# O projeto usa:
# 
# Tailwind CSS para responsividade e aparência moderna
# 
# Font Awesome para os ícones (ex: ícone da calculadora e troca de moedas)
# 
# Google Fonts com tipografia digital (Orbitron + Roboto)
# 
# Efeitos como:
# 
# Botões que brilham ao passar o mouse
# 
# Animação de pulso no botão "="
# 
# Bordas neon com gradientes roxos e cibernéticos
# 
# ⚙️ Funcionalidades Internas
# Lógica de cálculo feita em JavaScript puro (sem bibliotecas externas)
# 
# Alternância entre abas Standard e Currency via DOM e classes CSS
# 
# Lógica de conversão de moeda com taxas pré-definidas (poderia ser expandido para usar uma API como ExchangeRates ou OpenExchange)
# 
# 💡 Resumo Visual
# Aba	Função	Destaque Visual
# Standard	Cálculos básicos (AC, CE, %, +, -, /...)	Botões brilhantes e visor digital
# Currency	Conversor de moedas fixo	Dropdowns, resultado animado