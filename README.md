```
namespace TasosKyr;

class About extends Me
{

    public function getBasicInfo(): array
    {
        return [
            'name' => [
                'first' => 'Anastasios (Tasos)',
                'last' => 'Kyrtsis',
            ],
            'based_in' => [
                'city' => 'Berlin',
                'country' => 'Germany'
            ],
        ];
    }
    
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Klarna',
                'position' => 'Software Engineer'         
            ]
        ];
    }

    public function getFavouriteTechnologies(): array
    {
        return [
            Javascript::class,
            Typescript::class,
            Reactjs::class,
            Vuejs::class,
            Nextjs::class,
            Jamstack::class,
            styled-components::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
