# Data Engineer Ass1_Postgres
The Assignment requires a postgres database sparkifydb for a music app, Sparkify. The database is a start schame that has 1 fact table and 4 dimension tables

## Fact Table
**songplays** - records in log data associated with song plays i.e. records with page NextSong <br>
songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent

## Dimension Tables
**users** - users in the app  <br>
user_id, first_name, last_name, gender, level <br>
**songs** - songs in music database  <br>
song_id, title, artist_id, year, duration <br>
**artists** - artists in music database <br>
artist_id, name, location, latitude, longitude <br>
**time** - timestamps of records in songplays broken down into specific units <br>
start_time, hour, day, week, month, year, weekday <br>

# Run Python Scripts
- Create tables
``` python create_table.py ```

- Execute ETL
``` python etl.py ```