Install & Download 
shell

git clone https://github.com/masrursam/Multi-TransTx.git

shell

npm install ethers cfonts readline dotenv fs

edit your RPC URL & Private key on here
nano .env

Then ctrl x y enter

run it 
node index.js

Watch the video

Extract address :
powershell

Select-String -Pattern "Address: (\S+)" yourfile.txt | ForEach-Object { $_.Matches.Groups[1].Value } | Out-File addresses.txt
