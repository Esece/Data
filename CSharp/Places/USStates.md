# US States

Read-only objects
``` csharp
sealed class USState
{
    public static readonly USState AL = new USState { Code = "AL", StateName = "Alabama" };
    public static readonly USState AK = new USState { Code = "AK", StateName = "Alaska" };
    public static readonly USState AZ = new USState { Code = "AZ", StateName = "Arizona" };
    public static readonly USState AR = new USState { Code = "AR", StateName = "Arkansas" };
    public static readonly USState CA = new USState { Code = "CA", StateName = "California" };
    public static readonly USState CO = new USState { Code = "CO", StateName = "Colorado" };
    public static readonly USState CT = new USState { Code = "CT", StateName = "Connecticut" };
    public static readonly USState DE = new USState { Code = "DE", StateName = "Delaware" };
    public static readonly USState FL = new USState { Code = "FL", StateName = "Florida" };
    public static readonly USState GA = new USState { Code = "GA", StateName = "Georgia" };
    public static readonly USState HI = new USState { Code = "HI", StateName = "Hawaii" };
    public static readonly USState ID = new USState { Code = "ID", StateName = "Idaho" };
    public static readonly USState IL = new USState { Code = "IL", StateName = "Illinois" };
    public static readonly USState IN = new USState { Code = "IN", StateName = "Indiana" };
    public static readonly USState IA = new USState { Code = "IA", StateName = "Iowa" };
    public static readonly USState KS = new USState { Code = "KS", StateName = "Kansas" };
    public static readonly USState KY = new USState { Code = "KY", StateName = "Kentucky" };
    public static readonly USState LA = new USState { Code = "LA", StateName = "Louisiana" };
    public static readonly USState ME = new USState { Code = "ME", StateName = "Maine" };
    public static readonly USState MD = new USState { Code = "MD", StateName = "Maryland" };
    public static readonly USState MA = new USState { Code = "MA", StateName = "Massachusetts" };
    public static readonly USState MI = new USState { Code = "MI", StateName = "Michigan" };
    public static readonly USState MN = new USState { Code = "MN", StateName = "Minnesota" };
    public static readonly USState MS = new USState { Code = "MS", StateName = "Mississippi" };
    public static readonly USState MO = new USState { Code = "MO", StateName = "Missouri" };
    public static readonly USState MT = new USState { Code = "MT", StateName = "Montana" };
    public static readonly USState NE = new USState { Code = "NE", StateName = "Nebraska" };
    public static readonly USState NV = new USState { Code = "NV", StateName = "Nevada" };
    public static readonly USState NH = new USState { Code = "NH", StateName = "New Hampshire" };
    public static readonly USState NJ = new USState { Code = "NJ", StateName = "New Jersey" };
    public static readonly USState NM = new USState { Code = "NM", StateName = "New Mexico" };
    public static readonly USState NY = new USState { Code = "NY", StateName = "New York" };
    public static readonly USState NC = new USState { Code = "NC", StateName = "North Carolina" };
    public static readonly USState ND = new USState { Code = "ND", StateName = "North Dakota" };
    public static readonly USState OH = new USState { Code = "OH", StateName = "Ohio" };
    public static readonly USState OK = new USState { Code = "OK", StateName = "Oklahoma" };
    public static readonly USState OR = new USState { Code = "OR", StateName = "Oregon" };
    public static readonly USState PA = new USState { Code = "PA", StateName = "Pennsylvania" };
    public static readonly USState RI = new USState { Code = "RI", StateName = "Rhode Island" };
    public static readonly USState SC = new USState { Code = "SC", StateName = "South Carolina" };
    public static readonly USState SD = new USState { Code = "SD", StateName = "South Dakota" };
    public static readonly USState TN = new USState { Code = "TN", StateName = "Tennessee" };
    public static readonly USState TX = new USState { Code = "TX", StateName = "Texas" };
    public static readonly USState UT = new USState { Code = "UT", StateName = "Utah" };
    public static readonly USState VT = new USState { Code = "VT", StateName = "Vermont" };
    public static readonly USState VA = new USState { Code = "VA", StateName = "Virginia" };
    public static readonly USState WA = new USState { Code = "WA", StateName = "Washington" };
    public static readonly USState WV = new USState { Code = "WV", StateName = "West Virginia" };
    public static readonly USState WI = new USState { Code = "WI", StateName = "Wisconsin" };
    public static readonly USState WY = new USState { Code = "WY", StateName = "Wyoming" };

    public string Code { get; private set; }
    public string StateName { get; private set; }

    private USState() {}
}
```

Enum (State Codes)
``` csharp
enum USStateCode
{
    AL,
    AK,
    AZ,
    AR,
    CA,
    CO,
    CT,
    DE,
    FL,
    GA,
    HI,
    ID,
    IL,
    IN,
    IA,
    KS,
    KY,
    LA,
    ME,
    MD,
    MA,
    MI,
    MN,
    MS,
    MO,
    MT,
    NE,
    NV,
    NH,
    NJ,
    NM,
    NY,
    NC,
    ND,
    OH,
    OK,
    OR,
    PA,
    RI,
    SC,
    SD,
    TN,
    TX,
    UT,
    VT,
    VA,
    WA,
    WV,
    WI,
    WY,
}
```

Enum (State Names)
``` csharp
enum USState
{
    Alabama,
    Alaska,
    Arizona,
    Arkansas,
    California,
    Colorado,
    Connecticut,
    Delaware,
    Florida,
    Georgia,
    Hawaii,
    Idaho,
    Illinois,
    Indiana,
    Iowa,
    Kansas,
    Kentucky,
    Louisiana,
    Maine,
    Maryland,
    Massachusetts,
    Michigan,
    Minnesota,
    Mississippi,
    Missouri,
    Montana,
    Nebraska,
    Nevada,
    NewHampshire,
    NewJersey,
    NewMexico,
    NewYork,
    NorthCarolina,
    NorthDakota,
    Ohio,
    Oklahoma,
    Oregon,
    Pennsylvania,
    RhodeIsland,
    SouthCarolina,
    SouthDakota,
    Tennessee,
    Texas,
    Utah,
    Vermont,
    Virginia,
    Washington,
    WestVirginia,
    Wisconsin,
    Wyoming,
}
