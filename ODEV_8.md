# Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

# 1- test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
	CREATE TABLE employee (
	id integer PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE NOT NULL,
	email VARCHAR(100)
	);
# 2- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
	insert into employee (id, name, birthday, email) values (1, 'Earvin Lansbury', '1941-04-11', 'elansbury0@techcrunch.com');
insert into employee (id, name, birthday, email) values (2, 'Kessiah Carlick', '1938-03-06', 'kcarlick1@usgs.gov');
insert into employee (id, name, birthday, email) values (3, 'Seth Padden', '2003-05-25', 'spadden2@amazon.co.jp');
insert into employee (id, name, birthday, email) values (4, 'Clarine Cossell', '1926-01-04', 'ccossell3@japanpost.jp');
insert into employee (id, name, birthday, email) values (5, 'Say Blake', '1953-10-30', 'sblake4@foxnews.com');
insert into employee (id, name, birthday, email) values (6, 'Karilynn Doxey', '1949-11-25', 'kdoxey5@cdc.gov');
insert into employee (id, name, birthday, email) values (7, 'Kaela Brauninger', '2004-07-12', 'kbrauninger6@narod.ru');
insert into employee (id, name, birthday, email) values (8, 'Harley Swindell', '1926-04-11', 'hswindell7@ftc.gov');
insert into employee (id, name, birthday, email) values (9, 'Fields Bolletti', '2014-05-10', 'fbolletti8@yellowbook.com');
insert into employee (id, name, birthday, email) values (10, 'Moyna Rickis', '2023-01-10', 'mrickis9@yellowbook.com');
insert into employee (id, name, birthday, email) values (11, 'Kissee Donlon', '2015-11-15', 'kdonlona@edublogs.org');
insert into employee (id, name, birthday, email) values (12, 'Stephen Giotto', '1921-10-13', 'sgiottob@comsenz.com');
insert into employee (id, name, birthday, email) values (13, 'Jory Antwis', '1986-12-12', 'jantwisc@princeton.edu');
insert into employee (id, name, birthday, email) values (14, 'Eryn Melding', '2009-03-28', 'emeldingd@mlb.com');
insert into employee (id, name, birthday, email) values (15, 'Lisle Cobbold', '1944-08-18', 'lcobbolde@imdb.com');
insert into employee (id, name, birthday, email) values (16, 'Man O''Bradain', '2021-02-10', 'mobradainf@imdb.com');
insert into employee (id, name, birthday, email) values (17, 'Durant Osgorby', '1924-03-11', 'dosgorbyg@arizona.edu');
insert into employee (id, name, birthday, email) values (18, 'Sophie Dumbrell', '1929-07-03', 'sdumbrellh@google.co.uk');
insert into employee (id, name, birthday, email) values (19, 'Kimberley Skeech', '2006-06-27', 'kskeechi@nbcnews.com');
insert into employee (id, name, birthday, email) values (20, 'Carola Bignall', '2009-12-13', 'cbignallj@posterous.com');
insert into employee (id, name, birthday, email) values (21, 'Ninnette Allin', '1984-07-01', 'nallink@cyberchimps.com');
insert into employee (id, name, birthday, email) values (22, 'Rori Muttock', '2017-05-15', 'rmuttockl@upenn.edu');
insert into employee (id, name, birthday, email) values (23, 'Charmain Guiu', '1947-09-02', 'cguium@imdb.com');
insert into employee (id, name, birthday, email) values (24, 'Karie Birdwhistle', '1941-07-15', 'kbirdwhistlen@guardian.co.uk');
insert into employee (id, name, birthday, email) values (25, 'Briant Caesman', '1943-05-15', 'bcaesmano@blogspot.com');
insert into employee (id, name, birthday, email) values (26, 'Bob Tattersill', '1951-07-23', 'btattersillp@geocities.com');
insert into employee (id, name, birthday, email) values (27, 'Yolanda Leele', '1992-07-17', 'yleeleq@bloomberg.com');
insert into employee (id, name, birthday, email) values (28, 'Mildred Brunetti', '1981-09-05', 'mbrunettir@washingtonpost.com');
insert into employee (id, name, birthday, email) values (29, 'Pyotr Pirolini', '1929-12-31', 'ppirolinis@ning.com');
insert into employee (id, name, birthday, email) values (30, 'Edmon Bridgland', '1984-03-08', 'ebridglandt@forbes.com');
insert into employee (id, name, birthday, email) values (31, 'Linzy Emberton', '1990-11-12', 'lembertonu@elegantthemes.com');
insert into employee (id, name, birthday, email) values (32, 'Martie Gerrans', '1979-10-15', 'mgerransv@mail.ru');
insert into employee (id, name, birthday, email) values (33, 'Jordon Cradick', '1970-02-06', 'jcradickw@deviantart.com');
insert into employee (id, name, birthday, email) values (34, 'Jermain Runnicles', '1969-09-27', 'jrunniclesx@eepurl.com');
insert into employee (id, name, birthday, email) values (35, 'Auroora Carlick', '2021-06-21', 'acarlicky@squarespace.com');
insert into employee (id, name, birthday, email) values (36, 'Nari Renshell', '1992-09-26', 'nrenshellz@ameblo.jp');
insert into employee (id, name, birthday, email) values (37, 'Sanson Antonsen', '1978-10-23', 'santonsen10@ihg.com');
insert into employee (id, name, birthday, email) values (38, 'Bibbye Hugonneau', '1963-02-26', 'bhugonneau11@businessweek.com');
insert into employee (id, name, birthday, email) values (39, 'Darla Alner', '2016-02-25', 'dalner12@nhs.uk');
insert into employee (id, name, birthday, email) values (40, 'Silvano Cicco', '2022-11-06', 'scicco13@answers.com');
insert into employee (id, name, birthday, email) values (41, 'Constantina Killner', '1979-12-02', 'ckillner14@joomla.org');
insert into employee (id, name, birthday, email) values (42, 'Stillman Heggman', '1952-04-09', 'sheggman15@barnesandnoble.com');
insert into employee (id, name, birthday, email) values (43, 'Desi Wordley', '1968-09-04', 'dwordley16@oracle.com');
insert into employee (id, name, birthday, email) values (44, 'Luther Olivetti', '2010-05-05', 'lolivetti17@printfriendly.com');
insert into employee (id, name, birthday, email) values (45, 'Sisely Kuschke', '1968-06-07', 'skuschke18@whitehouse.gov');
insert into employee (id, name, birthday, email) values (46, 'Michel Caslake', '2015-05-05', 'mcaslake19@mashable.com');
insert into employee (id, name, birthday, email) values (47, 'Zabrina Serfati', '2002-11-25', 'zserfati1a@ed.gov');
insert into employee (id, name, birthday, email) values (48, 'Madelon Glanfield', '2022-02-27', 'mglanfield1b@mail.ru');
insert into employee (id, name, birthday, email) values (49, 'Seward Symon', '1922-05-10', 'ssymon1c@de.vu');
insert into employee (id, name, birthday, email) values (50, 'Lorne Vallantine', '1958-01-12', 'lvallantine1d@paginegialle.it');
# 3- Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
	UPDATE employee
	SET
	name ='UpdatedName',
	birthday='2000-01-01',
	email= 'updated@updated'
	WHERE id between 10 and 15;

	UPDATE employee
	SET
	name ='xxxxxxxx',	
	email= 'xxxx@xxxx'
	WHERE id in (5, 15)
	returning *;
# 4- Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
	DELETE FROM employee
	where id=10;
	
	delete from employee
	where name like 'A%'
	returning *;

	delete from employee
	where birthday between '1930-01-01' and '1970-01-01'
	returning *;
