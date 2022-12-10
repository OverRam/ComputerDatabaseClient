# Client

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

client to API 
https://github.com/OverRam/ComputerDatabaseApi

This client connects via rest API.
Currently, you can: Search for a computer by name or purchase date, then you can sort the results.
Add the computer to the database, then the server fills in the field of the purchase cost in PLN after conversion from the date of purchase and then returns the result to the client, this result is downloaded by the user in the XML format.

Format:

`<faktura><br>
    <komputer><br>
        <date>2022-12-20</date><br>
        <name>kompu</name><br>
        <costUsd>213</costUsd><br>
        <costPln>0</costPln><br>
    </komputer><br>
    <komputer><br>
        <date>2022-12-20</date><br>
        <name>kompu</name><br>
        <costUsd>213</costUsd><br>
        <costPln>0</costPln><br>
    </komputer><br>
</faktura>`
