# Análise e Comparação de Genomas
## Introdução:

A seguir está um _pipeline_ computacional usado para realizar a análise e a comparação dos BGCs (Clusters de Genes Biossintéticos) de vários genomas de linhagens diferentes de uma mesma espécie, usando o NCBI e antiSMASH, programas online e gratuítas. O _pipeline_ foi criado por Katherine Bilsland Marchesan e Luiza Rodrigues de Souza no IFSP (Instituto Federal de São Paulo), Campus Campinas.

## Indicações:
- Nós usamos a database NCBI como fonte dos genomas, mas você também pode usar um outro banco de dados, portanto, as instruções para obtenção dos genomas podem variar.

## Instruções
### Obtendo os Genomas:
- Primeiramente, abre o NCBI: https://www.ncbi.nlm.nih.gov/datasets/genome/
- Em seguida, pesquise pela espécie que você quer analisar.
- Escolha a primeira linhagem desejada e realize o download do seu arquivo FASTA (_Genome sequences_) apertando nos três pontos.
- Com o download feito, extrai o seu arquivo FASTA abrindo a pasta da seguinte maneira:
```
“Nome da pasta”.zip  >  ncbi_dataset  >  data  >  “1° pasta”  >  “sua linhagem”.FASTA
```
- Crie uma pasta em um local acessível, e copie este arquivo FASTA para sua pasta.
- Repita esses passos até obter a quantidade de linhagens desejadas na sua pasta.
### Rodando os Genomas pelo antiSMASH:
- Com isso feito, abre o antiSMASH: https://antismash.secondarymetabolites.org/#!/start
- No campo ```Data input```, aperte em ```Upload file``` e selecione o primeiro arquivo .FASTA na pasta que você criou.
- Opcionalmente entra o seu email, deixe os outros campos nas configurações default e aperta em ```Submit``` para iniciar a análise.
- Repita isso com todos os outros arquivos .FASTA\
***Dica: É possível iniciar várias análises simultaneamente em diferentes abas do seu navegador.**


## Observações:
- Também seria possível usar o NCBI _Accession Number_ (coluna: RefSeq) no antiSMASH  para realizar o download do genoma direto do NCBI, porém nós não conseguimos fazer isso funcionar para nós.

## Contato:
katherine.b@aluno.ifsp.edu.br

luiza.souza@aluno.ifsp.edu.br
