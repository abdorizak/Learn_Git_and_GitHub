<p align="center">
  <img width="500" src="./Logo.png" alt="Learn Git and GitHub">
</p>
<h1 align="center">Baro Git & GitHub</h1>
<p align="left">
  keydkani waxaa ugu Tala Galay In Ardayda iyo Junior developers ka ay ka baran karaa Nidamka Git kaaso oo ku sahlaya in Account kaaga Github ka Repository yadiisa aa la xariiri kartid, Hadii Aadan Hore U Aqoon Dhib Maleh Waxan ku bari Doonaa halkan Hadaba Hadii Adan Horey u leheen Samayso Account adiga oo Gujinaya -> <a href="https://github.com/" target="_blank">GitHub</a>.
</p>

## Waa Maxay Git & GitHub?
kaba soo qaad waxaa Lashaqaynaysaa Team kuwaas oo Sameynayaan Project `Online Registration` waaxaa lagu soo asign Gareeyey Task,
sidee ula shaqeyn lahayd kooxdaas oo u qori lahayd code isla mar ahaantas iyaga iyo adi isku code ah waliba isku project isla mar ahaantas, ayado oo laga Foganaya Khilaaf. Hagaag, taasi waa meesha git iyo gitHub ama gitLab, ka soo galaan.
- waa Maxay `Git`?
<p align="left">
git waa Version Control System, dhab ahaantii waa nidaamka hoose ee ku shaqeeya qaab local ah.
</p>

- Waa Maxay `GitHub` ama `GitLab`?
<p align="left">
waa Nidaam Online ah kaas oo logu talagalay in lagu kaydiyo, lagu lasocda software projects ka taas oo keeni karta in developers badan ay kawada shaqayn karaan project ayaka oo adeegsanaya nidamka git si ay ulaqaybqatan hadba project markas la hayaho.
</p>

## <h1 align="left">faa'iidooyin ka Git and GitHub</h1>
- waxaa ow kuu sahlaa in aad daba gali karto/ Tracking isbadalka project kaaga.
- in aad Team Devlopers la shaqayn karto project.
- in aad la xariiri karto repository kaaga adiga oo adegsanaya CLI (Command Line Interface) kaaga, waliba samaynaa push pull GitHub Repository.

<h3 align="left">Waa Maxay Repository?</h3>
waa meel aad ku kayd sankarto project kaaga.

## <h1 align="left">Amarada aasaasiga ah ee Git</h1>
- `git config` waxa uu Git-ka baraa qafka aad tahay, asaga oo keydinaya magaacaga iyo email kaaga si loogu istcmaalo `git commits` kaaga.
- `git init` waxaa lugu abuura Git repository cusub.
- `git clone` waxa uu soo dajiyaa copy-ga project remote repository(sida `GitHub` ama `GitLab`) saaran.
- `git add` hal file ama ka badan ayuu ku daraa meesha diyaarinta(staging area).
- `git commit` waxa uu si taxana ah `Git` ka ugu keydiyaa faylasha isbadaka lugu sameeyay.
- `git status` waxa uu soo tixaa faylasha aad wax ka badashay iyo kuwa aadan wali `git add` ama `git commit` ku sameyn.
- `git push` faylasha aad soo commit gareysay ayuu remote repository(sida `GitHub` ama `GitLab`) saaraa.
- `git remote` local repository-ga ayuu remote repository (sida `GitHub` ama `GitLab`) ku xiraa.
- `git branch` waxa uu kuu sahlaa in aad projecti-gaaga laamo u qeybiso si ay developers-ka ugu fududaato in midkastaahi shaqadiisa 
   si madaxbanaan u qabsado. `git branch` waxaa lugu abuurikaraa, arkikaraa ama tirikaraa laamaha projectiga.
- `git checkout` waxaa loo isticmaala sameynta branch cusub iyo in asaga loo wareego, sidookale branches horay u jiray ayaa la isaga gudbi karaa.
- `git pull` waxaa lugu helaa update-yadii u dambeeyay ee ka dhacay remote repository-ga.
- `git merge` isbadalada brach ka dhaca ayuu branch kale u gudbiyaa, tusaale: developers-ka shaqooyinka ay branch-yada kaladuwan ku soo qabtaan 
   ugu dambeyn Main-ka ayey ku soo wareejiyaan.
- `git log` waxa uu soo bandhigaa branch-ga markaas la joogo commits-ka laga sameeyay.

## <h1 align="left">Sidee loogu Shubtaada Git Computer kaaga</h1>
### windows
* Si'aad u setup gareyso git waxaad u baahantahay in aad lasoo dagto programkan hadii aad isticmaalayso window adiga oo raacaya [Link]('https://git-scm.com/downloads').

### mac
* Si'aad u setup gareyso git waxaad u baahantahay in aad isticmaahso `HomeBrew` oo ku fududeynaayo in aad ku shubato `git` marka hore hobi in ow kugu jiro `brew` hadii ow san kugu jirin soo dagso [Home Brew]('https://brew.sh/') ama isticmaal command kan si aad ugu shubato:
```terminal
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
kadib ku shubo `git`:
```terminal
brew install git
```

### Linux
isticmaal Command-gan soosocdo si aad ugu shubato `git` linux-kaaga:
```terminal
sudo apt install git-all
```

# sidee Project local ah loosoo saraa Github ama GitLab adiga oo adeegsanayo amarada git.
- Marka Hore waxaad u bahantahay in soo furto `Terminal` ama `Command-Line Interface` adiga oo tagaya Project meeshisa / `Folder directory` kadib adeegsanaya Amarada/commands git.
- kadib qor amradan/commands kan 
  - `git init` oo ah abuur repositery cusub
  - `git add ` isticmaal marka aad adegsanayso command gan calamada `.` oo micnaheedu yahay dhamaan hal-mar kuwad shub repositery-ga files-ka, hadii aad hore u sameysay balse file aad wax kabadashay waxaad samayn kartaa isla command-gan adiga oo dhahaya tusaale: `git add file.js` command-gan waxow ku samaynayaa in aad kaliya file kas saarankarto repositery-gaaga
  - Kadib samey commit adiga oo adegsanaya commad-gan `git commit -m 'waxa aad samaysay ku qeexaya halkan'`
  - hadii aadan hore ugu link-gareysnayn github link-gaaga ama gitLab kaaga isticmaal command-gan `git remote add <git URL>`.
  -kadib push garey adiga oo adeegsanaya command-ga `git push origin main` hadii repositery-gaaga `master` yahay kubadal meesha `main` adiga oo qoraya sidan `git push origin Master`.


## Wax ku darso mashruuca
Si aan u ogaado in aad wax ka fahantay waxaan lagaaga Bahanyahay qodobadan Soosocda:
- Fork ku dhaho Project-ga kontadaada asaasiga ee GitHub.
- Samey Json file adiga oo ku dhex abuuraaya directory-ka `./contributers/{magacaaga}.json` kuna dhex qorayaa sidatan.
```json
{
  "name": "Magacaaga",
  "university": "Jamacada aad dhigatid / kasoo baxday",
  "description": "Faahfaahin ku qor halkan.",
}
```

## Mahadsanidin Dhamaan (Contributers)
<a href = "https://github.com/abdorizak/Learn_Git_and_GitHub/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=abdorizak/Learn_Git_and_GitHub"/>
</a>



<h4 align="center">© 2022 Abdorizak, iOS Engineer || Mohamud A. Abshir, Front-End Engineer || Samir Samawade, Mobile Developer </h4>