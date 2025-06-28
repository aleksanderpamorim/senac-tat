Diretório dos comandos do Linux Mint
📁 Comando ls – Listar arquivos e diretórios
O comando ls é usado no terminal Linux para listar o conteúdo de diretórios.

✅ Opções -lh (combinadas)
-l: Mostra a lista detalhada, com permissões, dono, tamanho, data etc.

-h: Exibe os tamanhos dos arquivos em formato legível (KB, MB, GB...), junto com -l.

📌 Exemplo:
bash
Copiar
Editar
ls -lh
Resultado: Uma lista com os arquivos e diretórios do local atual, mostrando detalhes como:

Permissões (rwx)

Nome do dono

Tamanho (ex: 2.1K, 5.3M)

Data da última modificação

Nome do arquivo/diretório
📁 mkdir (make directory)
Cria novos diretórios (pastas) no sistema.

📌 Exemplo:

bash
Copiar
Editar
mkdir nova_pasta
➡ Cria uma pasta chamada nova_pasta.

💧 pv (pipe viewer)
Mostra o progresso de dados sendo transferidos, útil em comandos com cat, dd, tar etc.

📌 Exemplo:

bash
Copiar
Editar
pv arquivo.iso > /dev/null
➡ Exibe uma barra de progresso ao ler o arquivo arquivo.iso.
Aqui está a diferença entre caminho absoluto e caminho relativo em formato de tabela:

Tipo de Caminho	Definição	Exemplo	Base de Referência
Absoluto	Caminho completo a partir da raiz (/) do sistema.	/home/aleksander/Documentos/arquivo.txt	Sempre começa do diretório raiz /
Relativo	Caminho em relação ao diretório atual onde você está no terminal.	../Documentos/arquivo.txt	Depende da posição atual

🔎 Resumo:
Absoluto: sempre funciona, independente de onde você esteja.

Relativo: depende de onde você está no sistema no momento.
🗑️ rm -v – Remover arquivos com detalhes
rm: Remove (deleta) arquivos ou diretórios.

-v: (verbose) Mostra na tela o nome de cada arquivo removido.

📌 Exemplo:
bash
Copiar
Editar
rm -v teste.txt
➡ Remove o arquivo teste.txt e mostra:

nginx
Copiar
Editar
removed 'teste.txt'
Se quiser remover diretórios com conteúdo, aí usamos rm -rv (com -r de recursivo).
