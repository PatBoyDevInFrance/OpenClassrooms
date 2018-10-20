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
// Ajout du code en entier dans la classe MainActivity
public class MainActivity extends AppCompatActivity {

    private DrawerLayout drawerLayout;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        drawerLayout = (DrawerLayout) findViewById( R.id. drawerLayout );
    }
    // Test pour commit
    @Override
    public boolean onCreateOptionsMenu(Menu menu) {
        getMenuInflater().inflate(R.menu.main_menu, menu );
        return true;
    }


}
     
