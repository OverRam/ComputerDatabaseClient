# Client

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

client to API 
https://github.com/OverRam/ComputerDatabaseApi

This client connects via rest API.
Currently, you can: Search for a computer by name or purchase date, then you can sort the results.
Add the computer to the database, then the server fills in the field of the purchase cost in PLN after conversion from the date of purchase and then returns the result to the client, this result is downloaded by the user in the XML format.

Format:

<faktura>
    <komputer>
        <date>2022-12-20</date>
        <name>kompu</name>
        <costUsd>213</costUsd>
        <costPln>0</costPln>
    </komputer>
    <komputer>
        <date>2022-12-20</date>
        <name>kompu</name>
        <costUsd>213</costUsd>
        <costPln>0</costPln>
    </komputer>
</faktura>
