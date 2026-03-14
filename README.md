io# kabilan0712-IBM-Project
git remote add origin https://github.com/kabila0712/Kabilan0712.git
git branch -M main
git push -u origin mainecho "# Kabilan0712" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kabila0712/Kabilan0712.git
git push -u origin mainfunction onCondition() {

    if (g_form.getValue('state') == '6') {   // 6 = Resolved

        g_form.setMandatory('close_code', true);
        g_form.setMandatory('close_notes', true);

    } else {

        g_form.setMandatory('close_code', false);
        g_form.setMandatory('close_notes', false);

    }

}
