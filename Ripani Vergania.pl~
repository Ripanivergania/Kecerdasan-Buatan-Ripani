famale(mary).
famale(liza).
famale(amy).
famale(karen).
male(david).
male(john).
male(ray).
male(peter).

couple(david,amy).
couple(jack,karen).
couple(john,susan).

brothersister(liza,john).
brothersister(susan,ray).
brothersister(peter,mary).

grandfa(david,jack).
grandma(army, karen).
boy(john,ray).
girl(liza,susan).
grandchild(peter,mary).

besan(david,karen).
besan(jack,amy).

onty(liza).
uncle(ray).
nephew(peter,mary).

is_perempuan(A) :-famale(A).
is_lakilaki(B) :-male(B).
is_suamidanistri(A,B) :-couple(A,B).
is_anaklakilaki(A,B) :-boy(A,B).
is_anakperempuan(A,B) :-girl(A,B).
is_saudara(A,B) :-brothersister(A,B).
is_kakek(A1,A2) :-grandfa(A2,A1).
is_nenek(B2,B1) :-grandma(B1,B2).
is_besan(A,B) :-besan(A,B).
is_bibipetermary(A) :-onty(A).
is_pamanpetermary(A) :-uncle(A).
is_keponakan_liza_ray(A,B) :-nephew(A,B).
is_cucu(A,B) :-grandchild(A,B).
not(sah(menikah(A,B))):-is_saudara(A,B).
sah(menikah(A,B)):-is_suamidanistri(A,B).


