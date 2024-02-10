Do stuff with the prod database?

In app:
RAILS_ENV=production rails console

From CLI:

psql -h dpg-cn3e2jvqd2ns73eh7j40-a.ohio-postgres.render.com -U christopher_james_dent_user christopher_james_dent

Run prod migrations and seeds (should not have to do this again)
RAILS_ENV=production rails db:migrate
RAILS_ENV=production rails db:seed
