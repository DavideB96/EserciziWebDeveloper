<!DOCTYPE html>
<html lang="it">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Esercizio Tabella</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            height: 100px;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: white;
            margin-top: 250px;
        }

        table {
            width: 600px;
            border-collapse: collapse;
            background-color: white;
            border: solid black;
        }

        th {
            background-color: green;
            color: white;
            padding: 12px;
            text-align: center;
        }

        td {
            padding: 12px;
            text-align: center;
            border-bottom: 1px solid black;
        }

        .ChangeColor {
            background-color: rgb(251, 246, 239);
        }
    </style>
</head>

<body>

    <table>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Cognome</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Davide</td>
                <td>Bianchi</td>
                <td>davidebianchi08@gmail.com</td>
            </tr>
            <tr class="ChangeColor">
                <td>Marco</td>
                <td>Bianchi</td>
                <td>marco.bianchi@gmail.com</td>
            </tr>
            <tr>
                <td>Angela</td>
                <td>Bianchi</td>
                <td>angela.bianchi@gmail.com</td>
            </tr>
            <tr class="ChangeColor">
                <td>Saverio</td>
                <td>Bianchi</td>
                <td>saverio.bianchi@gmail.com</td>
            </tr>
        </tbody>
    </table>

</body>

</html>
