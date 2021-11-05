# getMonth_php
Une fonction qui retourne le nom et le short name du mois 

function getMonth(int $mois)
    {
        $retour = null;
        $short = null;
        switch ($mois) {
            case 1:
                $retour = "Janvier";
                $short = "Janv.";
                break;
            case 2:
                $retour = "février";
                $short = "févr.";
                break;
            case 3:
                $retour = "Mars";
                $short = "Mars.";
                break;
            case 4:
                $retour = "Avril";
                $short = "Avri.";
                break;
            case 5:
                $retour = "Mai";
                $short = "Mai.";
                break;
            case 6:
                $retour = "Juin";
                $short = "Juin.";
                break;
            case 7:
                $retour = "Juillet";
                $short = "Juil.";
                break;
            case 8:
                $retour = "Août";
                $short = "Août.";
                break;
            case 9:
                $retour = "Septembre";
                $short = "Sept.";
                break;
            case 10:
                $retour = "Octobre";
                $short = "Oct.";
                break;
            case 11:
                $retour = "Novembre";
                $short = "Nov.";
                break;
            case 12:
                $retour = "Décembre";
                $short = "Déc.";
                break;
            default:
                $retour = "Invalide !.";
                $short = "null";
                break;
        }
        return [$retour, $short];
    }
    
    Lire sur updevcommunity : https://updevcommunity.com/app/post/comment-convertir-le-numero-du-mois-en-string-avec-php
