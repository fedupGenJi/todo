# RUNNING FOR THE FIRST TIME:
*PYTHON--3.13.00*\
(YOU CAN CREATE A VIRTUAL ENV TO THE FOLDER, SO THE VERSIONS DON'T GET MIXED UP)\
&emsp; &emsp; -INSTALL FLASK: pip install flask\
&emsp; &emsp; -and remeber to use Jinja-2 Snipper Kit by Wyatt Ferguson\


#IF NOT USING THE PROVIDED DB, configure DB through python:\
>>from app import app, db\
>>app.app_context().push()\
>>db.create_all()\
