# Table-olusturmek-guncellemek-silemek

## Merhabalar

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.


2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.


3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.


4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.


## Cevaplar: 


1. 
```sql

create table employe (
	id serial primary key,
	name varchar(50),
	birthday date,
	email varchar(100)
);


```

2. 
```sql

insert into employe (name, birthday, email) values ('Tarrance Burnhill', '2013-08-29', 'tburnhill0@live.com');
insert into employe (name, birthday, email) values ('Kiel Begin', '2007-09-16', 'kbegin1@wp.com');
insert into employe (name, birthday, email) values ('Eachelle Haggerty', '2002-05-26', 'ehaggerty2@facebook.com');
insert into employe (name, birthday, email) values ('Mario Morbey', '2001-01-05', 'mmorbey3@nature.com');
insert into employe (name, birthday, email) values ('Donetta Jozsa', '2008-09-01', 'djozsa4@opera.com');
insert into employe (name, birthday, email) values ('Minnnie Faithfull', '2017-01-06', 'mfaithfull5@wikispaces.com');
insert into employe (name, birthday, email) values ('Chancey Greenall', '2016-01-02', 'cgreenall6@ucoz.ru');
insert into employe (name, birthday, email) values ('Gae Brentnall', '2004-01-01', 'gbrentnall7@vk.com');
insert into employe (name, birthday, email) values ('Mayer Buckberry', '2004-03-28', 'mbuckberry8@deliciousdays.com');
insert into employe (name, birthday, email) values ('Meredithe Fassan', '2011-12-14', 'mfassan9@indiatimes.com');
insert into employe (name, birthday, email) values ('Dorine Beldan', '2013-12-17', 'dbeldana@booking.com');
insert into employe (name, birthday, email) values ('Giulia Millard', '2010-02-27', 'gmillardb@si.edu');
insert into employe (name, birthday, email) values ('Riki Beech', '2006-07-15', 'rbeechc@dyndns.org');
insert into employe (name, birthday, email) values ('Farra Albrooke', '2017-05-14', 'falbrooked@sciencedirect.com');
insert into employe (name, birthday, email) values ('Annabel Bonhan', '2011-12-26', 'abonhane@youtu.be');
insert into employe (name, birthday, email) values ('Roch Aughton', '2019-12-17', 'raughtonf@cdbaby.com');
insert into employe (name, birthday, email) values ('Sterne Raincin', '2006-12-01', 'sraincing@skyrock.com');
insert into employe (name, birthday, email) values ('Towney Evenden', '2001-12-05', 'tevendenh@csmonitor.com');
insert into employe (name, birthday, email) values ('Kirby Dionisetto', '2021-10-29', 'kdionisettoi@stumbleupon.com');
insert into employe (name, birthday, email) values ('Steffen Gabbott', '2005-08-22', 'sgabbottj@blogtalkradio.com');
insert into employe (name, birthday, email) values ('Prince MacAdie', '2007-08-28', 'pmacadiek@nature.com');
insert into employe (name, birthday, email) values ('Jorry Hearmon', '2004-12-09', 'jhearmonl@omniture.com');
insert into employe (name, birthday, email) values ('Jammie Pavy', '2003-04-28', 'jpavym@mtv.com');
insert into employe (name, birthday, email) values ('Barnebas Mazzeo', '2008-04-26', 'bmazzeon@hc360.com');
insert into employe (name, birthday, email) values ('Fifi Pittle', '2022-02-28', 'fpittleo@spotify.com');
insert into employe (name, birthday, email) values ('Madelena Leeder', '2007-12-30', 'mleederp@census.gov');
insert into employe (name, birthday, email) values ('Genna Cabel', '2004-07-18', 'gcabelq@apache.org');
insert into employe (name, birthday, email) values ('Lucian Buckby', '2006-11-23', 'lbuckbyr@virginia.edu');
insert into employe (name, birthday, email) values ('Onfroi Tomala', '2003-10-26', 'otomalas@barnesandnoble.com');
insert into employe (name, birthday, email) values ('Annabal Djurevic', '2009-07-08', 'adjurevict@reddit.com');
insert into employe (name, birthday, email) values ('Laurie Kennedy', '2008-12-07', 'lkennedyu@shop-pro.jp');
insert into employe (name, birthday, email) values ('Sigvard Prydie', '2010-04-18', 'sprydiev@tripod.com');
insert into employe (name, birthday, email) values ('Leopold Daton', '2014-08-01', 'ldatonw@elpais.com');
insert into employe (name, birthday, email) values ('Georgeanna Tattersill', '2010-08-17', 'gtattersillx@arstechnica.com');
insert into employe (name, birthday, email) values ('Basil Matei', '2016-05-01', 'bmateiy@fema.gov');
insert into employe (name, birthday, email) values ('Al Coldtart', '2015-11-25', 'acoldtartz@princeton.edu');
insert into employe (name, birthday, email) values ('Antonin Mulvin', '2000-09-02', 'amulvin10@cloudflare.com');
insert into employe (name, birthday, email) values ('Candide Boxhall', '2020-01-08', 'cboxhall11@cornell.edu');
insert into employe (name, birthday, email) values ('Jania Veronique', '2010-06-05', 'jveronique12@gov.uk');
insert into employe (name, birthday, email) values ('Buddie Gooddie', '2016-04-03', 'bgooddie13@weibo.com');
insert into employe (name, birthday, email) values ('Naoma Guisot', '2016-08-10', 'nguisot14@rakuten.co.jp');
insert into employe (name, birthday, email) values ('Hillel Igonet', '2009-11-03', 'higonet15@cafepress.com');
insert into employe (name, birthday, email) values ('Blair Belverstone', '2012-08-24', 'bbelverstone16@jigsy.com');
insert into employe (name, birthday, email) values ('Lionello Bonnefin', '2001-12-16', 'lbonnefin17@ask.com');
insert into employe (name, birthday, email) values ('Flossie Jirak', '2011-03-30', 'fjirak18@imdb.com');
insert into employe (name, birthday, email) values ('Ros Lefort', '2009-01-06', 'rlefort19@elegantthemes.com');
insert into employe (name, birthday, email) values ('Gusty Wooffitt', '2009-10-31', 'gwooffitt1a@bbc.co.uk');
insert into employe (name, birthday, email) values ('Fletch Simonitto', '2013-03-09', 'fsimonitto1b@merriam-webster.com');
insert into employe (name, birthday, email) values ('Nolie Grindlay', '2017-08-03', 'ngrindlay1c@digg.com');
insert into employe (name, birthday, email) values ('Dorey Dauney', '2012-01-31', 'ddauney1d@tinypic.com');


```


3. 
```sql

update employe  set 
name = 'Nikaniki Pinchen', 
birthday = '2018-08-24', 
email = 'npinchen2n@goo.ne.jp' 
Where id = 1;


update employe  set 
name = 'Gannie Finlaison',
birthday = '2002-10-01', 
email = 'gfinlaison2o@sciencedirect.com' 
Where id = 2;

update employe  set 
name = 'Madelena Hardes', 
birthday = '2016-10-04', 
email = 'mhardes2p@boston.com'
Where id = 3;


update employe  set 
name = 'Teodoor Ramet', 
birthday = '2003-11-24', 
email = 'tramet2q@berkeley.edu'
Where id = 4;

update employe  set 
name = 'Ban Jacobson', 
birthday = '2011-03-26', 
email = 'bjacobson2r@freewebs.com'
Where id = 5;


```


4. 
```sql


DELETE FROM employe Where id<6 RETURNING *;


```

**KOLAY GELSIN**