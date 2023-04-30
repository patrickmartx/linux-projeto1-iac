<h1>PROJETO 1: Script para criação de usuários, grupos e manipulação de permissões.</h1>

<div>Desenvolvido por Patrick Martins através do BootcampAWS da DIO</div>
<br>
<div>Nesse desafio foi desenvolvido um arquivo de Script chamado <a href="https://github.com/patrickmartx/linux-projeto1-iac/blob/main/iac1.sh">iac1.sh</a>
foram criados quatro diretórios, três grupos e nove usuários, sendo estes:</div>
<br>

| Diretórios   | Grupos        | Usuários      |
| :----------- | ------------: | ------------: |
| /publico     | GRP_ADM       | carlos        |
| /adm         | GRP_VEN       | maria         |
| /ven         | GRP_SEC       | joao          |
| /sec         |               | debora        |
|              |               | sebastiana    |
|              |               | roberto       |
|              |               | josefina      |
|              |               | amanda        |
|              |               | rogerio       |

<br>
<div>Os usuários tem Senha123 como senha padrão, cria-se automaticamente uma pasta para estes na /home e já está definido o shell bash como o padrão. Além da definição de quais grupos pertencem já estarem definidos também na mesma linha.</div>
<br>
<div>Após criar os dados, irá inserir os usuários nos grupos, sendo divididos em três usuários para cada grupo, na ordem especificada na tabela.</div>
<br>
<div>Com isso, é feito também as permissões de manipulação dos grupos nas pastas criadas, cada uma tendo liberdade total de alteração na sua especificada 
(exemplo: GRP_ADM tem acesso a leitura, alteração e execução da pasta adm), mas cada uma dessas pastas tendo como dono o root.</div>
<br>
</div>A pasta /publico permite com que qualquer um tenha acesso total de rwx.</div> 







