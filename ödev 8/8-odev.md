# 1. GÖrev
test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```SQL
CREATE TABLE employee (
id SERIAL PRIMARY KEY,
name VARCHAR(50) NOT NULL,
email VARCHAR(100),
birthday DATE
);
```
# 2. GÖrev
Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```SQL
insert into employee (name, email, birthday) values ('Cherianne', 'cpinkard0@w3.org', '2024-08-16');
insert into employee (name, email, birthday) values ('Allyson', 'amoyne1@wiley.com', '2024-01-06');
insert into employee (name, email, birthday) values ('Eve', 'ebatteson2@google.com', '2023-12-10');
insert into employee (name, email, birthday) values ('Jacinda', 'jshurville3@tripadvisor.com', '2023-11-20');
insert into employee (name, email, birthday) values ('Malina', 'misitt4@ucoz.com', '2024-01-01');
insert into employee (name, email, birthday) values ('Ethelred', 'ebeasant5@phoca.cz', '2024-06-28');
insert into employee (name, email, birthday) values ('Lemmie', 'lsecrett6@epa.gov', null);
insert into employee (name, email, birthday) values ('Nigel', 'nbraunton7@ebay.com', '2024-05-26');
insert into employee (name, email, birthday) values ('Lottie', 'lmichael8@archive.org', '2024-03-11');
insert into employee (name, email, birthday) values ('Milly', 'mrome9@amazon.co.jp', '2024-03-25');
insert into employee (name, email, birthday) values ('Gracie', 'gyesa@cargocollective.com', '2023-11-13');
insert into employee (name, email, birthday) values ('Horten', 'hcorrob@shop-pro.jp', '2024-06-04');
insert into employee (name, email, birthday) values ('Jamison', 'jcosgravec@home.pl', null);
insert into employee (name, email, birthday) values ('Haydon', 'hscraneyd@barnesandnoble.com', null);
insert into employee (name, email, birthday) values ('Windy', 'wgilffillande@printfriendly.com', '2024-04-07');
insert into employee (name, email, birthday) values ('Moises', 'mockwellf@wsj.com', '2024-04-29');
insert into employee (name, email, birthday) values ('Winona', 'wzoppog@parallels.com', '2024-06-23');
insert into employee (name, email, birthday) values ('Quintana', 'qwrackh@ameblo.jp', '2024-03-14');
insert into employee (name, email, birthday) values ('Haleigh', 'hcosbyi@deliciousdays.com', '2023-12-07');
insert into employee (name, email, birthday) values ('Karita', 'khouldj@hugedomains.com', '2023-12-19');
insert into employee (name, email, birthday) values ('Petr', 'psedenk@spotify.com', '2023-11-27');
insert into employee (name, email, birthday) values ('Remington', 'rdodmanl@cargocollective.com', '2024-01-31');
insert into employee (name, email, birthday) values ('Alfons', 'azukerm@yahoo.com', null);
insert into employee (name, email, birthday) values ('Jackson', 'jbrotherickn@so-net.ne.jp', '2023-12-18');
insert into employee (name, email, birthday) values ('Delora', 'dbielbyo@csmonitor.com', '2024-02-25');
insert into employee (name, email, birthday) values ('Cesar', 'ckernockep@marriott.com', '2024-05-08');
insert into employee (name, email, birthday) values ('Blanche', 'bcoldtartq@youku.com', '2024-06-20');
insert into employee (name, email, birthday) values ('Avram', 'acasolr@slashdot.org', '2024-05-08');
insert into employee (name, email, birthday) values ('Gerrard', 'gpauluccis@hibu.com', '2024-04-21');
insert into employee (name, email, birthday) values ('Andi', 'ahydechamberst@phpbb.com', '2024-04-17');
insert into employee (name, email, birthday) values ('Hamil', 'hlongu@indiegogo.com', '2024-03-11');
insert into employee (name, email, birthday) values ('Chilton', 'cthackrayv@seattletimes.com', '2024-06-15');
insert into employee (name, email, birthday) values ('Kingston', 'kdoodsonw@dot.gov', '2024-08-01');
insert into employee (name, email, birthday) values ('Ruthy', 'rwignallx@bizjournals.com', '2024-06-13');
insert into employee (name, email, birthday) values ('Nannette', 'ncheesworthy@surveymonkey.com', '2024-04-26');
insert into employee (name, email, birthday) values ('Jesse', 'jwinsborrowz@sourceforge.net', null);
insert into employee (name, email, birthday) values ('Romona', 'rolford10@patch.com', '2024-04-19');
insert into employee (name, email, birthday) values ('Willie', 'wgamell11@lulu.com', '2023-11-18');
insert into employee (name, email, birthday) values ('Ives', 'islocket12@nytimes.com', '2024-08-18');
insert into employee (name, email, birthday) values ('Ross', 'rwoodes13@dion.ne.jp', '2023-11-03');
insert into employee (name, email, birthday) values ('Jayme', 'jsach14@timesonline.co.uk', null);
insert into employee (name, email, birthday) values ('Maighdiln', 'malty15@tuttocitta.it', '2024-09-17');
insert into employee (name, email, birthday) values ('Inger', 'iiredell16@sakura.ne.jp', '2023-10-06');
insert into employee (name, email, birthday) values ('Rod', 'raddie17@geocities.com', '2024-01-06');
insert into employee (name, email, birthday) values ('Jennee', 'jclitheroe18@salon.com', '2024-03-18');
insert into employee (name, email, birthday) values ('Caldwell', 'calwood19@163.com', '2024-03-04');
insert into employee (name, email, birthday) values ('Suzi', 'ssantoro1a@jalbum.net', '2024-09-18');
insert into employee (name, email, birthday) values ('Hanny', 'hkenaway1b@toplist.cz', null);
insert into employee (name, email, birthday) values ('Phillie', 'pcoenraets1c@loc.gov', '2024-09-24');
insert into employee (name, email, birthday) values ('Carline', 'csumbler1d@cdbaby.com', '2024-07-13');

```
# 3. GÖrev
Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```SQL
UPDATE employee
SET name = 'Mert',
	email = 'inselmert4672@gmail.com',
	birthday = '2004-01-04'
WHERE id = 1;

UPDATE employee
SET name = 'Burak',
	email = 'canturkburak@gmail.com',
	birthday = '1453-12-23'
WHERE id = 2;


UPDATE employee
SET name = 'Gokhan',
	email = 'sugokhan@gmail.com',
	birthday = '1985-07-13'
WHERE id = 3;

UPDATE employee
SET name = 'Ertan',
	email = 'ertandinler@gmail.com',
	birthday = '1999-03-21'
WHERE id = 4


UPDATE employee
SET name = 'Olcay',
	email = 'olcay@gmail.com',
	birthday = '1999-03-21'
WHERE id = 5

```
# 4. GÖrev
Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```SQL
DELETE FROM employee
WHERE id = 12 OR id = 13 OR id = 14 OR id = 15 OR id = 16

```