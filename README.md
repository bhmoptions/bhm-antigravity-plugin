# BHM Markets para Google Antigravity

Plugin para o Google Antigravity para consultar dados de opções brasileiras, comparar volatilidades e simular cenários hipotéticos com a BHM Markets. Não executa ordens.

## Instalação

Clone este repositório para a pasta de plugins do seu usuário no Antigravity:

### Windows (PowerShell)
```powershell
git clone https://github.com/bhmoptions/bhm-antigravity-plugin.git "$HOME\.gemini\config\plugins\bhm-markets"
```

### Linux / macOS
```bash
git clone https://github.com/bhmoptions/bhm-antigravity-plugin.git ~/.gemini/config/plugins/bhm-markets
```

### Escopo do projeto (opcional)
Se preferir instalar apenas para o projeto atual, clone dentro da pasta do repositório:
```bash
git clone https://github.com/bhmoptions/bhm-antigravity-plugin.git .agents/plugins/bhm-markets
```

Reinicie o Antigravity após a instalação para carregar o plugin e suas ferramentas.

## Autenticação e Acesso

* Exige conta BHM com **assinatura paga** ou **teste grátis ativo**.
* Na primeira chamada a uma ferramenta BHM, o Antigravity solicitará autorização e abrirá o navegador para login seguro na BHM.
* Os limites de uso são 100 consultas por dia, 10 por minuto e 2 simultâneas por conta.
