# my management
make -C packages/ios-mana/src
in project-meta-data.xml add
    <package>
      <name>ios-mana</name>
      <local/>
  </package>

ncs-project update –y
