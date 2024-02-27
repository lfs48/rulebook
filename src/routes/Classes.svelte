<script>
    import ClassTraits from '$lib/class_traits.svelte';
</script>

<section>
    <h1>Chapter 3: Classes</h1>
    <p>
        A <b>class</b> is a heroic archetype
        which defines your role and abilities.
    </p>

    <section>
        <h2>Warrior</h2>
        <p>
            Warriors are mighty brutes who solve problems with unrestrained violence.
        </p>

        <ClassTraits>
            <h3>Warrior Traits</h3>
            <td slot='hp'>10</td>
            <td slot='armor'>Light and heavy armor, shields</td>
            <td slot='attacks'>All melee weapons</td>
            <td slot='defenses'>FORT, REF, FREE, PERS</td>
        </ClassTraits>

        <div>
            <h3>Starting Equipment</h3>
            <ul>
                <li>A heavy melee weapon; or a medium melee weapon and a shield; or two light melee weapons.</li>
                <li>A suit of light or heavy armor.</li>
            </ul>
        </div>

        <h3>Warrior Core Features</h3>

        <article>
            <h4>Wild Strkes</h4>
            <p>
                When you take the Strike action, you can spend 3 Resource
                to make one additional physical attack as part of that action.

                At 4th level, when you use Wild Strikes, all attacks you perform
                as part of that action deal an extra 1 damage on at least a partial hit.

                At 7th level, the extra damage increases to 2.
            </p>
        </article>

        <h3>Warrior Major Features</h3>

        <article>
            <h4>Cleave</h4>
            <p>
                When you perform a physical melee attack,
                you can choose up to two targets rather than one.
            </p>
        </article>

        <article>
            <h4>Unrelenting</h4>
            <p>
                When you take damage that would reduce you to 0 HP,
                you can spend 1 Resource to drop to 1 HP instead (ignore any leftover damage).
            </p>
        </article>

        <article>
            <h4>Brutal Critical</h4>
            <p>
                When you score a critical hit with a physical attack, double the attack's base damage.
            </p>
        </article>

        <h3>Warrior Specializations</h3>

        <article>
            <h4>Berserker</h4>
            <p>
                When you use Wild Strikes, you can enter a rage. While raging, the following effects apply:
            </p>
            <ul>
                <li>You get a bonus die on all physical melee attacks.</li>
                <li>Your AC, FOC, and WILL are sundered.</li>
            </ul>
            <p>
                Your rage lasts until you end your turn without attacking or being attacked.
            </p>
        </article>

        <article>
            <h4>Runecarver</h4>
            <p>
                When you gain this feature, choose three 1st rank Elemental spells.
                You learn the chosen spells. CON is your spellcasting attribute for them,
                and you have class proficiency with them.
                When you use Wild Strikes, you can spend 1 additional Resource
                to cast one of those spells as part of that action.
            </p>
        </article>

        <h3>Warrior Boons</h3>

        <article>
            <h4>Battle Rites</h4>
            <p>
                During a rest, you can perform special rites to amp yourself up for battle
                (e.g. applying war paint, communing with spirits, war dancing).
                By doing so, your next use of Wild Strikes costs no Resource.
            </p>
        </article>

        <article>
            <h4>Charge!</h4>
            <p>
                During the first round of combat only, you get the following benefits:
            </p>
            <ul>
                <li>You get a +10 bonus to your initiative.</li>
                <li>You get an extra movement point.</li>
            </ul>
        </article>

    </section>
</section>