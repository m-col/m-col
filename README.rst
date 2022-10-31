.. code-block:: haskell

    instance User MC where
        type Dev MC = (FOSS, Neuroscience)

        loves = [Wayland, Python, Haskell]
        studying = [Haskell] >>= 🧠

        working =
            case now of
                Night -> Qtile
                Day -> Improbable

        links =
            Links
                { fediverse = "mcol@fosstodon.org"
                , web = "mcol.xyz"
                , repos = "mcol.xyz/code"
                }

.. image:: https://github-readme-stats.vercel.app/api?username=m-col&count_private=true&title_color=fff&icon_color=79ff97&text_color=fefefe&bg_color=0a0c10&hide_title=true
   :alt: mcol's GitHub stats
