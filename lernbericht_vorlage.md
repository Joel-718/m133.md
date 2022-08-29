# Lern-Bericht
✍️Joel Freitas

## Einleitung

✍️ Wie speichert und leitet man ein Value von einem Texfeld.

## Was habe ich gelernt?

✍️ Ich habe gelernt, wie man Daten von einem textfield speichert und dies dan zu einer neuen Seite weiter leitet.

## Beschreibung
```xhtml
        <h:form>
            <h:outputLabel for="eingabe" value="Ihr Name "/> 
            <h:inputText value="#{helloManagedBean.eingabe}" id="eingabe"/>
            <h:commandButton value="Submit Query" action="post_1.xhtml"/>
        </h:form>
```

```java
  public HelloManagedBean() {
    }
    
    private String eingabe;

    public String getEingabe() {
        return eingabe;
    }

    public void setEingabe(String eingabe) {
        this.eingabe = eingabe;
    }
```

![image](https://user-images.githubusercontent.com/69576108/187228907-aa338cf6-1b7c-41d2-bca4-98cd7714e322.png)
![image](https://user-images.githubusercontent.com/69576108/187229019-1e2f173e-687a-45f8-a8ba-337bf1a1d545.png)


## Verifikation



# Reflektion zum Arbeitsprozess

👍 
Zu beginn hatte ich etwas schwierigkeiten mit dem umgang von JSP, doch nach einer viertel Stunde hatte ich ein ganz gutet Überblick über den Konzept.

👎
Wie schon vorher erwähnt hatte ich etwas start schwierigkeiten, da bei der html seite eine andere vorgehensweise ist und auch etwas anders geschrieben wird. Was mich etwas verwirrt hat, ist wie man dies mit Java verienen kann.


**VBV**: Ich will die Auftröge aufmerksam durchlesen, damit ich einen klaren Überblick habe.
