# HMVC Codeigniter Extension

Code ini bersumber dari: 
https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc/src/codeigniter-3.x/

Dimodifikasi untuk:
- Menambahkan directory modules(group)
```
/aplication
	/modules
		/group_module
			/module
				/controllers
				/models
				/views
		/group_module2
		/module
			/controllers
			/models
			/views
```
- Membatu extends controller
```
Modules::load('welcome');

class Satu extends Welcome 
```
- Membatasi adanya folder didalam controllers