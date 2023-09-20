# Typing_speed

words=['ability','able','about','above','accept','according','account','across',
'act','action','activity','actually','add','address','administration',
'admit','adult','affect','after','again','against','age','agency',
'agent','ago','agree','agreement','ahead','air','all','allow','almost','alone',
'along','already','also','although','always','American','among','amount',
'analysis','and','animal','another','answer','any','anyone','anything','appear',
'apply','approach','area','argue','arm','around','arrive','art','article',
'artist','as','ask','assume','at','attack','attention','attorney','audience',
'author','authority','available','avoid','away','baby','back','bad','bag','ball',
'bank','bar','base','be','beat','beautiful','because','become','bed','before',
'begin','behavior','behind','believe','benefit','best','better','between',
'beyond','big','bill','billion','bit','black','blood','blue','board','body',
'book','born','both','box','boy','break','bring','brother','budget','build',
'building','business','but','buy','by','call','camera','campaign','can','cancer',
'candidate','capital','car','card','care','career','carry','case','catch',
'cause','cell','center','central','century','certain','certainly','chair',
'challenge','chance','change','character','charge','check','child','choice',
'choose','church','citizen','city','civil','claim','class','clear','clearly',
'close','coach','cold','collection','college','color','come','commercial',
'common','community','company','compare','computer','concern','condition',
'conference','Congress','consider','consumer','contain','continue','control',
'cost','could','country','couple','course','court','cover','create','crime',
'cultural','culture','cup','current','customer','cut',
'dark','data','daughter','day','dead','deal','death','debate','decade','decide',
'decision','deep','defense','degree','Democrat','democratic','describe','design',
'despite','detail','determine','develop','development','die','difference',
'different','difficult','dinner','direction','director','discover','discuss',
'discussion','disease','do','doctor','dog','door','down','draw','dream','drive',
'drop','drug','during',
'each','early','east','easy','eat','economic','economy','edge','education',
'effect','effort','eight','either','election','else','employee','end','energy',
'enjoy','enough','enter','entire','environment','environmental','especially',
'establish','even','evening','event','ever','every','everybody','everyone',
'everything','evidence','exactly','example','executive','exist','expect',
'experience','expert','explain','eye',
'face','fact','factor','fail','fall','family','far','fast','father','fear',
'federal','feel','feeling','few','field','fight','figure','fill','film','final',
'finally','financial','find','fine','finger','finish','fire','firm','first',
'fish','five','floor','fly','focus','follow','food','foot','for','force',
'foreign','forget','form','former','forward','four','free','friend',
'from','front','full','fund','future',
'game','garden','gas','general','generation','get','girl','give','glass','go',
'goal','good','government','great','green','ground','group','grow','growth',
'guess','gun','guy',
'hair','half','hand','hang','happen','happy','hard','have','he','head','health',
'hear','heart','heat','heavy','help','her','here','herself','high','him',
'himself','his','history','hit','hold','home','hope','hospital','hot','hotel',
'hour','house','how','however','huge','human','hundred','husband',
'idea','identify','if','image','imagine','impact','important','improve','in',
'include','including','increase','indeed','indicate','individual','industry',
'information','inside','instead','institution','interest','interesting',
'international','interview','into','investment','involve','issue',
'it','item','its','itself','job','join','just','keep','key','kid','kill','kind',
'kitchen','know','knowledge','land','language','large','last','late','later',
'laugh','law','lawyer','lay','lead','leader','learn','least','leave','left',
'leg','legal','less','let','letter','level','lie','life','light','like','likely',
'line','list','listen','little','live','local','long','look','lose','loss',
'lot','love','low',
'machine','magazine','main','maintain','major','majority','make','man','manage',
'management','manager','many','market','marriage','material','matter','may',
'maybe','me','mean','measure','media','medical','meet','meeting','member',
'memory','mention','message','method','middle','might','military','million',
'mind','minute','miss','mission','model','modern','moment','money','month',
'more','morning','most','mother','mouth','move','movement','movie','much','music',
'must','myself','name',
'nation','national','natural','nature','near','nearly','necessary','need',
'network','never','new','news','newspaper','next','nice','night','no','none',
'nor','north','not','note','nothing','notice','now','number',
'occur','off','offer','office','officer','official','often',
'oil','old','on','once','one','only','onto','open','operation','opportunity',
'option','or','order','organization','other','our','out','outside','over',
'own','owner','page','pain','Painting','paper','parent',
'part','participant','particular','particularly','partner','party',
'pass','past','patient','pattern','pay','peace','people','per','perform',
'performance','perhaps','period','person','personal','phone','political',
'politics','poor','popular','population','position','positive','possible',
'power','quite','race','radio',
'raise','range','rate','rather','reach','read','ready','real','reality','realize',
'really','reason','receive','recent','recently','recognize','record','red',
'reduce','reflect','region','relate','relationship','religious','remain',
'remember','remove','report','represent','Republican','require','research',
'resource','respond','response','responsibility','run','safe','same','save',
'say','scene','school','science','scientist','score','sea','season','seat',
'second','section','security','see','seek','seem','sell','send','senior','sense',
'series','serious','serve','service',
'set','seven','several','shake','share','she','shoot','short','shot','should',
'shoulder','show','side','sign','significant','similar','simple','simply','since',
'sing','single','sister','sit','site','situation','six','size','skill','skin',
'small','smile',
'so','social','society','soldier','some','somebody','someone','something',
'sometimes','speech','spend','sport','spring','staff','stage','stand','standard',
'star','start','state','statement','station','stay','step','still','stock',
'stop','store','story','strategy','street','strong','structure','student','study',
'stuff','style','subject','success','successful','such','suddenly','suffer',
'suggest','summer','support','sure','surface','system','table','take','talk',
'task','tax','teach','teacher','team','technology','television','tell','ten',
'tend','term','test','than','thank','thing','think','third','this','those',
'though','thought','thousand','threat','three','through','throughout','throw',
'thus','time','to','today','together','tonight','too','top','total','tough',
'toward','town','trade','traditional','training','travel','treat','treatment',
'tree','trial','trip','trouble','true','truth','try','turn','TV','two','type',
'under','understand','unit','until','up','upon','us','use','usually','value',
'various','very','victim','view','violence','visit','voice','vote','wait',
'weapon','wear','week','weight','well','west','western','what','whatever',
'when','where','whether','whose','why','wide','wife','will','win','wind',
'window','wish','with','within','without','woman','wonder','word','work',
'worker','world','worry','would','write','writer','wrong','yard',
'yeah','year','yes','yet','you','young','your','yourself']


cx_Freeze Configuration for Building an MSI Installer

The provided code is a configuration script for cx_Freeze, a tool for building standalone executables and installers for Python applications. This script is specifically used to create an MSI (Microsoft Installer) installer for a Python application called "Typing Speed Increaser Game."

Configuration:

- `from cx_Freeze import *`: Import necessary modules from cx_Freeze.
- `includefiles`: A list of files to include in the installer package, which includes the "typing speed image.ico" file.
- `base`: A variable that determines the base of the application, especially on the Windows platform. If the platform is "win32," the base is set to "Win32GUI."
- `shortcut_table`: A list containing information about creating shortcuts for the installed application. In this case, it defines a shortcut named "DesktopShortcut" that will be created on the user's desktop.
  - "DesktopShortcut": Shortcut name.
  - "DesktopFolder": Directory on the user's desktop where the shortcut will be created.
  - "Typing Speed": Name of the shortcut.
  - "TARGETDIR": The directory where the application will be installed.
  - "[TARGETDIR]\Typingspeed.exe": Target executable file.
- `msi_data`: A dictionary that associates the "Shortcut" table with the shortcut_table defined earlier.
- `bdist_msi_options`: A dictionary that specifies options for building the MSI installer, including the data table.
- `setup`: The main setup function for configuring the build process.
  - `version`: Version number of the application.
  - `description`: Description of the application.
  - `author`: Author of the application.
  - `name`: Name of the application.
  - `options`: A dictionary specifying build options.
    - `build_exe`: Options related to building the executable, including the files to include.
    - `bdist_msi`: Options specific to creating the MSI installer, including the data table.
  - `executables`: List of Executable objects, each defining an executable script and its properties.
    - `script`: The main Python script (Typingspeed.py) to be bundled.
    - `base`: The base platform for the executable (set to "Win32GUI" for Windows).
    - `icon`: The icon file (typing speed image.ico) associated with the executable.

The provided script is used to configure cx_Freeze to build an MSI installer for the "Typing Speed Increaser Game" Python application. This MSI installer can be used to distribute and install the application on Windows systems.

Note: To use this script effectively, you should have cx_Freeze and its dependencies installed, and the script should be executed in a Python environment with cx_Freeze available.


Typing Speed Increaser Game - Python Application

This Python script implements a simple typing speed increaser game using the Tkinter library for the graphical user interface. The game aims to improve typing speed by presenting words that the player must type as quickly and accurately as possible within a time limit.

Key Components and Features:
- The game interface is created using Tkinter, with labels to display text and entry widgets for user input.
- Words for the game are stored in a list called "words," and they are randomly shuffled to present a new word for each round.
- The game includes a timer that counts down from 60 seconds, indicating the time remaining to complete as many words as possible.
- The player's score is displayed, showing the number of correctly typed words.
- Missed words are also tracked, and the total score (score - miss) is displayed when the game ends.
- The game includes a slider at the top to display the game's welcome message with a scrolling effect.
- Players can start typing words when the timer starts by pressing the Enter key after typing the word shown in the label.
- The game provides feedback on whether the typed word is correct, and the word label is updated with a new word for each round.
- When the game ends, a message box prompts the player to play again.
- The game's GUI elements are styled using different fonts and colors.

Instructions:
1. Launch the game, and the timer will start counting down from 60 seconds.
2. Type the word displayed in the "Type the Word" label.
3. Press the Enter key after typing the word to check if it's correct.
4. Your score increases for each correctly typed word.
5. The game tracks missed words.
6. When the timer reaches 0, your final score is displayed.
7. You can choose to play again or exit the game.

Components and Libraries Used:
- Tkinter: Used for creating the graphical user interface (GUI) elements.
- random: Used for shuffling words to present them randomly.
- messagebox: Used for displaying a message box for game restart confirmation.

Note:
- The script assumes that an icon file named "typing speed image.ico" is available in the same directory as the script. This icon is set for the game window.
- The list of words used in the game can be customized or extended as needed.

Enjoy improving your typing speed with this simple game!
