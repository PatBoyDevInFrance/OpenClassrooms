// Bout de code Android studio pour constituer un MenuBurger.

@Override
    public boolean onOptionsItemSelected(MenuItem item) {
        switch (item.getItemId()) {
            case R.id.hamburgerMenu:
                drawerLayout.openDrawer(Gravity.RIGHT);
                return true;
                default:
                    return super.onOptionsItemSelected(item);

        }

    }    
// insert code onCreatOptionsMenu
@Override
    public boolean onCreateOptionsMenu(Menu menu) {
 // j'ai extrait du code pour le TP OpenClassrooms
}     
