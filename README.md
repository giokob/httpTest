დააყენეთ შემდეგი პაკეტები:
conda install -c conda-forge python-magic

ტესტის გასაშვებად hosts ფაილში 127.0.0.1-ის გასწვრივ ჩაამატეთ example1.ge example2.ge

ტესტი ეშვება შემდეგი ბრძანებით
python run.py path/to/main.py config.json


changelog:
run.py: დაემატა ბონუსის ტესტი logTest (მადლობა გვანცას +2%)
basichttp: დაემატა mime-typeის შემოწმება; ამოწმებს დირექტორიაში არსებულ ყველა ფაილს; გადმოწერილი ფაილი მოწმდება ჰეშით.
rangeheader: დაემატა შემოწმება როცა range არის არასწორად გადაცემული
virtualhost: დაემატა ტესტები, აღარ არის დამოკიდებული basichttp-ზე

