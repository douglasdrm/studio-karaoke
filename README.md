# Studio Karaokê

Protótipo independente de editor de karaokê, publicado como site estático.

## Recursos disponíveis

- Interface responsiva em português
- Upload e reprodução local de áudio
- Sincronização manual por linha com prévia
- Edição de início/fim de cada verso
- Ajuste de cores, tamanho de fonte e estilo
- Salvamento local no navegador
- Exportação de LRC e JSON; importação de JSON

## Ainda não implementado

Remoção de vocais com IA, alinhamento automático por palavra, exportação de MP4, Backblaze e integração com sistema DJ.

## Hospedagem

Projeto estático, sem dependências de build. Na Vercel use **Framework Preset: Other**, **Build Command: vazio** e **Output Directory: .** (raiz). Arquivo inicial: `index.html`.

## Privacidade

Os arquivos de áudio selecionados não são enviados a servidor neste protótipo. O navegador mantém somente informações, letra, estilos e tempos em `localStorage`.
