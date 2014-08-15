# Download automatico do acervo dominiopublico.gov.br

Aqui estão uma série de scrits que automatizam o download
dos vídeos disponíveis no portal www.dominiopublico.gov.br

* 0wget-paginasdebusca.sh - gera o arquivo 1ids.txt a partir do conteúdo
das 17 páginas que listam os vídeos disponíveis no portal
* 1unifica-e-gera-links.php - remove os ids duplicados encontrados 
no arquivo 1ids.txt e imprime as URLs para download dos arquivos .mp4
e download da página com detalhes sobre os vídeos
* 2wget-detalhes.sh - faz o download dos arquivos .html com detalhes dos vídeos
* 2wget-videos.sh - faz download dos arquivos dos vídeos em formato .mp4 
