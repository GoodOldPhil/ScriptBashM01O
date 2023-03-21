# ScriptBashM01O
És un script en llenguatge bash el qual comprova si un equip (host) esta actiu o no.

# Requirements/ Installacion
* Sistema operatiu linux
* Terminal (per exemple, bash)
* Fitxer de l'script (checkconnection.sh)

# Usage
Primer de tot, cal donar permis d'execucio a l'script *checkconnection.sh*
```
chmod u+x checkconnection.sh
```

Una vegada l'usuari té permis d'execucio, ja podeu utilitzar l'script seguint la sintaxi següent:
```bash
./checkconnection.sh <HOSTNAME><N>
```
On `HOSTNAME` es la IP de l'equip que volem comprovar

On `N` es el temps en segons cada quant comprovara si esta actiu l'equip
