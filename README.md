# Otrzymujemy i wyprowadzamy całą listę kontaktów w postaci tabeli (console.table)

node index.js --action list https://monosnap.com/file/xhXrNZeZ1RmaLHMmvJd7y48yy4Jec4

# Otrzymujemy kontakt po id

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6 https://monosnap.com/file/wn4IBFbTjgtTZL7Plb5hycFIHZUXZo

# Dodajemy kontakt

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22 https://monosnap.com/file/j3w7Z3exzpoHN4CBwkruIC8UMPlxiQ

# Usuwamy kontakt

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH https://monosnap.com/file/LpfWX0pwCUEHdao5GY9wBReZupUTd2
