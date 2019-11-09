# ModuleGroupe12
TP de POO réalisé par le Groupe N°XII de L2IN univ-ndere 
#MOUNSANDEH FATIMA BEL MOCTAR
#MATRICULE:18A852FS

class CtrlGestCmpt:
    def Directeur(self):
    
        self.ClientCli
        self.FenListCmptFen
        def Dr (self,cli,Fen):
            self.Cli = cli
            self.Fen = Fen
def actionPerformed(self,e,FenGestCmp,Cli,Fen,comp,CtrlDepotCmpt,CtrlRetraitCmpt,true) :
    self.ActionEvent=e
    self.Fen = FenGestCmp()
    self.comp = Cli.getCompte(Fen.getCompte())
    Fen.setControleur( CtrlDepotCmpt(Fen, comp, Fen, Cli), CtrlRetraitCmpt(Fen, comp, Fen, Cli))
    Fen.setLabelNumCompte(comp.getNumCompte())
    Fen.setVisible(true)


ph=''
num=0

while ph !=2:
    print("\tMAIN MENU")
    print("\t1.LE DIRECTEUR DIRIGE LA BANQUE*******")
    print("\t2.EXIT*")
    print("\tselect your option(1-2)")
    ph=input()
    
# -*- coding: utf-8 -*
#IZANE PALOUMA NESTOR
#MATRICULE:18A038FS

class Gestionnaire:
    def Emprunt(self,Em):
        self.Emprunt=float(Em)
    def Gerecompte(self,Gcom):
        self.Gerecompte=float(Gcom)
    def Gsetionnaire(self,Emprunt,Gerecompte):
        if(Emprunt==0):
            print("Le client n'a rien emprunté = !!",self.UnEmprunt)
        else:
            print("Le client a une dette = !!",self.prêt)
    def getEm(self):
        return self.Emprunt
    def getGcom(self):
        return self.Gerecompte
    def add (self,Ajouter):
        self.Compte += Ajouter
        print("Le client ajouté est:".format(self.Emprunt))
        return self.Em
    def sub (self,Supprimer):
        self.Compte -= Supprimer
        print("Le client supprimé est:".format(self.Compte))
        return self.Em
    def mod (self,Modifier):
        self.Compte += Modifier
        print("Le client modifié est:".format(self.Gcom))
        return self.Gcom
    def take (self,Enregistrer):
        self.Compte += Enregistrer
        print("Le client enregistré est:".format(self.Compte))
ph=''
num=0

while ph != 5:
    print("\tMAIN MENU")
    print("\t1. AJOUTER CLIENT*")
    print("\t2. SUPPRIMER CLIENT*")
    print("\t3. MODIFIER CLIENT*")
    print("\t4. ENREGISTRER CLIENT*")
    print("\t5. EXIT*")
    print("\tSelect Your Option (1-5) ")
    
    ph=input()

    # -*- coding: utf-8 -*-
    
#OUSMANOU YAOUBA
#MATRICULE:18A052FS

class Contrôleur:
 def CtrlDepotCmpt (self,Fen,compte,Fenlist,Cli,com):
     self.FenGestCmp=Fen
     self.Compte=compte
     self.FenListCmpt=Fenlist
     self.Client=Cli
     self.Fen = Fen
     self.compte = com
     self.Fenlist =Fenlist
     self.Cli = Cli
 def ActionPerformed(self,ActionEvent,e,true,Fen) :
		self.test = true
		self.c = Fen.getMontant().toCharArray()
 def Used(self):
     if(self,self.i,self.false):
         self.i<0
         self.i>9
         self.i !=0
         self.i != 0
         self.i = 1
         def CtrlDepotCmpt (self,Fen,compte,Fenlist,Cli,com,javax):
             compte.ajoutArgent(Fen.getMontant())
             Fen.dispose()
             Fenlist.setListCompte(Cli.getlescomptesclient())
             javax.swing.JOptionPane.showMessageDialog("Montant non valide")
             
             
mp=''
num=0

while mp!=2:
    print("\tMAIN MENU")
    print("\t1.CONTROLER LES OPERATIONS JOURNALIERES*******")
    print("\t2.EXIT*")
    
    mp=input()
         
  # -*- coding: utf-8 -*-
#MOUDARIFOU MOHAMADOU
#MATRICULE:18B248FS
class Guichetier:
    def init (self,Stringupdate,getconnection,conn,String,codeClient,numCompte,e,a,destination,texte):
        def Connection (self,codeCli,num):
          self.conn=0
          self.codeClient=codeCli
          self.numCompte=num
          def  getNumCompte(self):
              return self.numCompte
          def ajoutArgent(self,montant):
              Stringupdate
              getconnection()
              stmt = conn.createStatement()
              update = String(" CALL depotCompte"+"("+montant +", "+codeClient +", "+numCompte +")")
              print(update)
              stmt.execute(update)
              conn.close()
              e.printStackTrace()
              def  retraitargent(self,montant):
                  Stringupdate
                  getconnection()
                  stmt = conn.createStatement()
                  update = String("CALL retraitCompte"+"("+montant +", "+codeClient +", "+numCompte +")")
                  print(update)
                  stmt.execute(update)
                  conn.close()
                  e.printStackTrace()
                  def init (self,nom,solde):
                      self.nom=nom
                      self.solde=solde
                      def depot (self,a):
                          som=(self.solde+self.a)
                          return som
                      def retrait (self,a):
                          som=(self.solde-self.a)
                          return som
                      def virervers(self):
                          self.a
                          self.comptedestination
                          retrait(a)
                          destination.deposer(a)
                          def afficher (self):
                             self.solde=texte
                             return texte
                         
                             print("L'opération à l'internationale!!!")
                             
nb=''
lum=0

while nb !=5:
     print("\tMAIN MENU")
     print("\t1.VERSEMENTS*****")
     print("\t2.RETRAIT*****")
     print("\t3.VIREMENTS*****")
     print("\t4.OPERATION INTERNATIONALE*****")
     print("\t5.EXIT*")
     print("\tSelect Your Option (1-5) ")
     nb = input()
                           
            
        
