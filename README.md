Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@Avijeet1 
1
00Avijeet1/html
 Code Issues 0 Pull requests 0 Projects 0 Wiki Security Insights Settings
Add files via upload

 master
@Avijeet1
Avijeet1 committed 6 minutes ago 
1 parent cf7410b commit cf2f8c9ec3b23ae6798f4454d9ea867ba045be9c
Showing  with 44 additions and 0 deletions.
 44  20191021 HTML-Tabellen.html 
@@ -0,0 +1,44 @@
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>HTML Tabellen</title>
    <style>
        /*Dies ist ein Kommentar*/
        table,th,td{
            border:1px solid black;
            border-collapse: collapse;
            width: 600px;
        }
        .gelb{
            background-color: yellow;
        }
        
    </style>
</head>
<body>
    <h1>Tabellen</h1>
    <table><!--Beginn einer Tabelle-->
        <tr><!--Beginn einer TabellenZEILE-->
            <th><!--Beginn einer TabellenKOPFZELLE-->
                Vorname
            </th><!--ENDE einer TabellenKOPFZELLE-->
            <th>Nachname</th>
            <th>Ort</th>
        </tr><!--Ende einer TabelleZEILE-->        
        <tr>
            <td>Georg</td>
            <td>Both</td>
            <td>Wien</td>            
        </tr>
        <tr>
            <td>Stefan</td>
            <td>Trölß</td>
            <td>Linz</td>
        </tr>

    </table><!--Ende einer Tabelle-->


</body>
</html> 
0 comments on commit cf2f8c9
@Avijeet1
 
 
Leave a comment

Attach files by dragging & dropping, selecting or pasting them.
 
 You’re receiving notifications because you’re watching this repository.
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
