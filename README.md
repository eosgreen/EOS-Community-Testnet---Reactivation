# EOS.IO-Community-Testnet-Reactivation

## Welcome to the EOS.IO Community Testnet

#### Run by:
[EOSIO.SE!](http://eosio.se) 

[EOSGREEN.IO!](https://eosgreen.io)

[EOS42.IO!](https://eos42.io)

[EOSDAC.IO!](https://eosdac.io)

The public community superhero testnet described in this repository is running the dawn-3.x branch.

For official documentation check: https://github.com/EOSIO/eos

The following instructions detail the process of getting the software, building it, running a node for community testnet.

### Clean install Linux

Clone the eos repository and run the build script.

    git clone https://github.com/eosio/eos --recursive
    cd eos
    git checkout tags/DAWN-2018-04-27-ALPHA
    git submodule update --recursive
    ./eosio_build.sh
    cd build
    sudo make install
    
Now you can copy binary files (mainly nodeos,cleos,keosd) located in:

    /usr/local/bin
    
or in local build folders:

    build/programs/

and paste it in a folder dedicated for your node (e.g /etc/eosio/node_00)

### Launching a node on Community Testnet

`nodeos` will need a properly configured config.ini file in order to work properly. You can download it from [here!](https://github.com/eosgreen/EOS.IO-Community-Testnet-Reactivation).

- Create `data-dir` folder for you node, for example `/etc/eosio/node_00/data-dir`
- Download files `config.ini` and `genesis.json` from git repository [here!](https://github.com/eosgreen/EOS.IO-Community-Testnet-Reactivation)
- Edit path to `data-dir/genesis.json` file in coonfig.ini
- Choose your producer name (in case you want to produce blocks) and create own EOS key pair (you can create key pair using cleos command `./cleos create key` or using key generator.
- Add you producer name and your keys in your `config.ini`.
- Connect your node to superhero network using `start.sh` script from [here!]( https://github.com/eosgreen/scripts).
- Please inform in telegram channel your node info: Server geographic location, Organisation/Website, node ip/domain, http port, p2p port, producer name, your public key.
- After providing information and node synchronization, let us know in telegram channel to activate your account as BP.


Congratulations - you are up and running as BP on Superhero Testnet!

# List of connected BP Nodes:
| BP Account Name | Address | Port (http) | Port (p2p) | Location | Organisation |
|-----------------|---------|-------------|------------|----------|--------------|
juggernaut|eosgreen.uk.to|8889|9875|UK|EOSgreen.io
storm|ctestnet.edenx.io|8888|62071|Vasteras, Sweden|EOSIO.se
batman|54.194.49.21|8833|9875|Ireland|eosDAC.io
tom|superhero.cryptolions.io|8897|9885|Ukraine|CryptoLions.Io
venom|venom.eoscalgary.com|80|9877|Canada, Calgary|EOS Cafe
joker|joker.superhero.eos.roelandp.nl|8763|9873|Amsterdam and Germany|RoelandP.nl/eos
hellboy|ctestnet.eosdetroit.com|8889|1339|US,Seattle|EOS Detroit
cyclops|bp7-d3.eos42.io|8888|9876|UK,London|EOS42
wakanda|superheroes.eosio.africa|8888|9876|South Africa,Johannesburg|EOS Africa
wakanda2|156.38.160.91|8888|9876|Africa|EOS Africa
spiderman|166.70.202.194|8080|9877|USA,UT,Salt Lake City|SaltBlock
jigsaw|18.188.52.250|8899|9889|USA, Ohio|Blockpro
ironman|ctest.eosnewyork.io|8887|9870|USA, Virgina|EOS New York
hook|35.195.161.56|8888|9876|Belgium|EOS Denmark
robin|159.89.197.162|8889|9877|Singapore|OracleChain
rogue|dawn3-seed.tokenika.io|8888|9876|Poland|Tokenika
daredevil|bp.blockgenic.io|8888|9876|USA, West Coast|Blockgenic
magneto|47.52.18.70|9000|9876|China|EOS Gravity
doom|120.27.130.60|8888|9876|China|91EOS
megatron|ctest.koreos.io|8888|9876|South Korea|koreos_io
superman|ctestnet.objectcomputing.com|8888|9876|USA,St. Louis|OCI
beast|test.eosys.io|8887|9875|Korea,Seoul|EOSYS
stealth|bp-test.eosasia.one|8888|9876|Korea,Seoul|EOS Asia
mystique|138.68.15.85|8888|9876|China|helloEOS
rita|47.88.222.80|8888|9876|Singapore|EOSGeek
riddler|54.233.222.22|8887|9875|Brazil,Rio de Janeiro|EOS Rio
ursula|39.108.231.157|8899|9877|China|SuperONE.io
aquaman|ctestnet.eoshenzhen.io|8888|9876|China,ShenZhen|EOShenzhen
elektra|eosbp.enjoyshare.net|8888|9876|China,ShenZhen|enjoyshare
skeletor|bpt1.eosbixin.com|8888|9876|Thailand,Bangkok|EOSBIXIN
gargamel|46.4.253.242|7615|7610|Spain|www.bitcoineos.fun
hulk|superhero-bp1.eosphere.io|8888|9876|Australia,Perth|EOSphere
xavier|138.68.238.129|8888|9875|USA, CA|EOSBR
batgirl|178.49.174.48|8888|9876|Russia, Novosibirsk|EOS Novosibirsk
spaceghost|superhero.worbli.io|8888|9876|USA, Ohio|Worbil
wonderwoman|wonderwoman.eosreal.io|8888|9876|India,Mumbai-AWS|EOSREAL
phoenix|eosbrazil.com|8891|9878|Brazil,Joinville|EOSBrazil
loki|35.202.41.160|8888|9876|Ohio,Dayton|spear.fund
