# Robô de Checklist Demissional — versão web

Aplicação estática para GitHub Pages. A planilha Excel e os dados do colaborador são processados no próprio navegador; não há API nem banco de dados.

## Publicação
Em **Settings → Pages**, selecione **Deploy from a branch**, branch `main`, pasta `/ (root)`.

## Uso
1. Abra o link publicado.
2. Importe a planilha Excel do SGP.
3. Digite nome ou matrícula e selecione o colaborador.
4. Informe a data de desligamento.
5. Configure o desconto de alimentação: alojado R$ 61,72/dia ou não alojado R$ 33,52/dia.
6. Informe a premiação e gere o Word.

## Privacidade
- A planilha e os dados digitados não são enviados pelo código a um servidor.
- As bibliotecas SheetJS e JSZip são carregadas de CDN pública; é necessária conexão à internet.
- O modelo Word publicado não deve conter dados pessoais reais.
- O GitHub Pages não oferece login ou controle de acesso por usuário. Publique apenas com autorização da empresa e conforme a política interna.
- Não envie planilhas de colaboradores para este repositório.

## Limites
A planilha é lida na primeira aba e espera Colaborador, Matrícula, CARGO, nomCcu e Admissão. Revise o primeiro Word gerado antes do uso oficial.