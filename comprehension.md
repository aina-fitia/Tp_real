ETU004685-ETU004695:
1- Ce qu'on comprend:
    -function dbconnent();
        -se connecter au base de donnee et affiche une erreur s'il arrive pas ca affiche une messsage d'erreur 
    -function getOneline();
        -get une ligne de la reponse de la requete 
    -function getAllline();
        get toutes les lignes des reponses de la requete 
    -function execute_query()
        -les fonctions INSERT,UPDATE,DELETE ne retourne rien ils ont juste besoin de se connecter au base de donnee c'est ce que fait cette fonction
    -function get_current_manager()
        -join dept_manager et employees pour avoir son nom  avec la condition where la date = '9999-01-01' c'est juste une date pour dire qu'il est le manager actuel
    -function add_departments()
        -on insert juste une nouveau departements dans la base de donnee
    -function update_departments()
        -on modifie le departement sans modifier la cle primaire
    -function add_employee()
        -meme contexte que add_departments
    -function update_employee()
        -meme contexte que update_departments
    -function getonedepartments()
        -avoir un departement grace a son id
    -function get_one_employee()
        -avoir a propose d'une seule employee grace a son id
    -function get_salary_history()
        -avoir l'historique de salaire d'un employee grace a son id
    -function get_title_history()
        -avoir l'historique grace  a son id 

2-Ce qu'on ne comprends pas :
    -function getalldepartments()
        -CONCAT
    -function getjobsstart()
        -la fonctinnement de cette fonction
        -pq utiliser group by et order by en meme temps
    -function changer_departements()
        -on ne comprends pas le key update
    -function make_departements()
        -on ne comprends pas  le key update
    -function remove_maanger()
        -pq il y a 2 to_date? on remove or qu'on faiit update 
    -function get_employees_by_department()
        -on comprends qu'il faut juste selectionner les employees qui travaillent dans un departement et limit c limiter la recherche mais OFFSET on ne comprends pas
    -function get_longest_title()
        -on ne comprends pas pq le IF dans DATEDIFF 
    - urlencode($emp_no) 
    -$dept_no ? get_current_manager($dept_no) : null

3-Les fonctions qu'on ne comprends pas:
    -CONCAT 
    -INNER JOIn
    -WHERE .... <>
    -OFFSET
    -%%%s%%
    -empty($conditions) ? '1=1' : implode(' AND ', $conditions);
    -trim
    -ceil
    -&rarr
    -&larr