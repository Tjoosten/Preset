# Preset package voor Laravel Framework 5.7 en hoger

Huidige versie is gebaseerd op Boostrap 4.2.0

## Installatie 

1. Installeer een nieuwe versie van laravel 5.7 (of hoger) en `cd` in de applicatie. 
2. Install de preset doormiddel van `composer require verhuur-platform/preset`. *Het registereren van de service provider, is niet nodig omdat deze automatisch geregistreerd word.*
3. Gebruik het `php artisan preset verhuur-platform` commando voor de basis preset. **Of** gebruik `php artisan preset verhuur-platform` voor de basis preset en de Authenticatie routering + views.
4. Voer het commando `npm install` uit. 
5. Voer het commando `npm run dev` uit. 
6. Configureer je database connectie in de applicatie. 
7. Voer het commando `php artisan migrate` uit voor de basis user table in je database. 
8. Voer het commando `php artisan serve` uit. Voor het opstarten van je lokale development server. 