<style>
    table {
    }
    tr {
        @apply
        text-left
        odd:bg-gray-800
    }
    tr td {
        @apply
        text-wrap
        p-1
    }
</style>

<table>
    <slot />
    <tr>
        <td>
            <b>Class HP</b>
        </td>
        <slot name='hp' />
    </tr>
    <tr>
        <td>
            <b>Armor</b>
        </td>
        <slot name='armor' />
    </tr>
    <tr>
        <td>
            <b>Attacks</b>
        </td>
        <slot name='attacks' />
    </tr>
    <tr>
        <td>
            <b>Defenses</b>
        </td>
        <slot name='defenses' />
    </tr>
</table>