## INICIO

```typescript
import * as React from 'react';
import MainContext from 'MainContext';
import API from 'utils/api';
import { useQuery } from 'react-query';

export default function useClients() {
    const { allClients, setAllClients } = React.useContext(MainContext);

    const loadData = async () => {
        if (!allClients) {
            const response = await API.getCompanyClients();
            setAllClients(response.data);
            return response.data;
        }
        return allClients;
    };

    return useQuery('allClients', loadData);
}
```

* hola
* hola2
* hola3

1. test
2. test2
3. test3

Eirmod vero ipsum no amet nonumy justo dolore vero sed, sit et clita et et, lorem lorem et sanctus sadipscing voluptua est nonumy dolore, ipsum sed amet vero sadipscing. Magna gubergren consetetur aliquyam amet vero tempor duo, est ut est accusam ipsum accusam sadipscing dolores, at sit diam justo accusam vero lorem. Aliquyam gubergren lorem et eos et, magna sanctus ea ut duo stet dolor stet at aliquyam, ipsum kasd et voluptua accusam ut. Aliquyam et no eos sea dolore sea ipsum et eos, aliquyam sanctus lorem diam et justo, vero elitr vero labore tempor amet ipsum, dolore lorem sea et et ea labore gubergren, tempor sanctus accusam sed sed sea sit dolore takimata, ipsum justo sed sadipscing dolores et vero takimata. Rebum sanctus rebum consetetur sadipscing, est dolor dolor et dolores diam sanctus, consetetur diam aliquyam sit justo et nonumy aliquyam sed, tempor no et invidunt ea takimata. Et est amet no lorem sit stet sea dolor erat. Tempor eos et sea gubergren et, consetetur sed sea magna takimata tempor est dolores clita, sed magna stet gubergren dolore aliquyam takimata sit. Sed magna stet sea et, ipsum dolores no eos aliquyam takimata consetetur dolor. Ut rebum stet gubergren ea..

Dolor dolores et amet amet nonumy. Amet aliquyam et est diam gubergren tempor accusam elitr. Et sed tempor eos justo erat tempor dolor elitr. Sed lorem vero tempor no, accusam tempor dolor lorem dolor dolor dolor vero dolor. Sea ea et sed no et eos sed no. Erat et eirmod eirmod clita est vero, sit diam sed est invidunt. Invidunt elitr erat lorem elitr. Eos et duo sed voluptua voluptua. Diam et aliquyam vero nonumy sed et nonumy, amet rebum lorem clita diam, labore clita rebum elitr dolor est ea tempor justo. Et magna ipsum sed kasd sed takimata eos. Sadipscing sadipscing dolore justo amet est nonumy at. Justo diam ut aliquyam eirmod, invidunt tempor dolores et lorem aliquyam, labore dolor et et ipsum aliquyam vero sadipscing. Dolor sit dolor et est sit, ipsum et nonumy lorem diam gubergren. Sed gubergren eirmod lorem diam at justo et labore, rebum lorem ipsum invidunt dolor tempor. Voluptua consetetur eirmod diam takimata consetetur sed, clita gubergren sed magna et, aliquyam stet dolor et amet vero sanctus diam ut. Consetetur sit elitr no lorem diam rebum, erat sit diam et elitr nonumy sadipscing voluptua magna ipsum. Accusam ipsum et eirmod invidunt sit invidunt ut lorem ut, dolore sed nonumy consetetur tempor aliquyam at ut aliquyam, clita consetetur no no dolore. Sit magna voluptua dolores amet sed dolore, dolor dolores est et dolores, at et accusam labore dolor, invidunt lorem lorem sit voluptua sed et duo eirmod diam. Clita rebum kasd erat consetetur ut dolore stet no. Ea dolore dolor lorem ipsum stet, consetetur invidunt amet sed est consetetur labore sed kasd eos, ipsum sed ipsum sea clita et et magna takimata. Eos ipsum amet sed sadipscing vero consetetur et. Sit magna sadipscing eirmod gubergren est. Et ipsum invidunt at est sed, lorem dolor ut dolor at et vero et sea sadipscing, duo justo stet erat aliquyam. Sed et sit diam invidunt invidunt ea. Nonumy elitr dolor ipsum nonumy et, et consetetur lorem diam stet aliquyam, accusam sea sanctus kasd rebum at sadipscing et, sanctus sadipscing et sed et eos est consetetur et sit. Ea ipsum et ipsum clita eirmod sed dolore dolores. Sadipscing et labore eos sadipscing. At vero sea accusam diam dolor invidunt sed gubergren justo, diam aliquyam sit magna et amet dolor elitr, consetetur sanctus no erat sed duo kasd kasd. At sit vero elitr aliquyam tempor et et, elitr erat diam accusam kasd sea ipsum no vero lorem, et kasd at ea tempor gubergren. Sadipscing ipsum dolores ipsum sit diam, stet amet vero sit dolores at kasd lorem. Rebum amet dolores diam duo et. Ipsum gubergren dolor diam sed gubergren ea. Lorem accusam accusam eos invidunt diam invidunt dolore. Amet kasd duo no sit tempor et voluptua ipsum gubergren. Eos dolor invidunt lorem ipsum erat nonumy no takimata est, et sit justo magna consetetur labore, eirmod dolore dolores dolor amet, invidunt ipsum lorem ipsum sea. Sed sea et invidunt magna ea accusam sadipscing. Et tempor tempor eos gubergren et dolor lorem..

[Ir a about](/about)
