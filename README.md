# 🎨 Tema Personalizado GLPI (Roxo e Laranja)

Este repositório contém um tema CSS totalmente personalizado para a interface do **GLPI**. Ele foi desenvolvido para modernizar o visual padrão do sistema, aplicando uma identidade visual baseada nas cores roxo e laranja, além de permitir a fácil substituição dos logotipos do sistema.

---

## ✨ O que este tema altera?

Este código atua diretamente nas principais áreas visuais do GLPI:

* **Sidebar (Menu Lateral):** Altera a cor de fundo para o roxo institucional (`#4b31ad`), ajusta a cor dos textos para branco para garantir contraste e destaca os links ativos.
* **Logotipo Interno (Layout Vertical):** Substitui o logotipo padrão no topo do menu lateral esquerdo por uma imagem personalizada.
* **Tela de Login (Welcome / Anonymous):** * Muda o fundo para a cor institucional.
    * Ajusta as cores dos formulários (fundo branco, texto preto).
    * Aplica a cor laranja (`#f77f00`) nas *labels* e títulos para destaque.
    * Substitui a logo central de entrada.
* **Dashboard:** Aplica bordas personalizadas e insere o logotipo quando o painel é exibido em modo Tela Cheia (*Fullscreen*) ou Embutido (*Embed*).

---

## 🚀 Como instalar e usar

A aplicação deste tema é muito simples e não exige a alteração dos arquivos *core* (originais) do GLPI.

### Passo 1: Preparar a sua Logo
Para que as imagens apareçam corretamente, você precisará hospedar o logotipo da sua empresa em um local acessível (pode ser na intranet, em um servidor web público ou na própria pasta pública do seu servidor GLPI).

### Passo 2: Editar o arquivo CSS
1. Faça o download ou copie o conteúdo do arquivo `glpi-theme.css` deste repositório.
2. Abra o arquivo em um editor de texto (como o Bloco de Notas, VS Code ou Notepad++).
3. Busque (Ctrl+F) pelo texto: `COLOQUE_A_URL_DA_SUA_LOGO_AQUI.png`.
4. Substitua esse texto pela **URL real** da sua imagem. *(Faça isso nas 3 vezes em que o texto aparece no código).*

### Passo 3: Aplicar no GLPI
Dependendo da versão do seu GLPI, existem duas formas principais de inserir esse CSS:
* **Nativamente:** Acesse `Administração` > `Entidades`, selecione a sua entidade, vá até a aba **Interface de Usuário** e cole o código no campo de **CSS Personalizado**.
* **Via Plugin:** Utilize plugins como *UI Tweaks* ou *Custom CSS* para injetar o código de forma global no sistema.

### Passo 4: Limpar o Cache
Após salvar, pressione `Ctrl + F5` (ou limpe o cache do seu navegador) na tela do GLPI para carregar as novas regras visuais.

---

## 🛠️ Manutenção e Dicas Importantes

* **Atualizações do GLPI:** O GLPI pode alterar o nome de algumas classes CSS em grandes
